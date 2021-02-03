
`set.seed(1000)`
`df_pca <- prcomp(df_sc)`
`summary(df_pca)`
`# Loadings for 1st and 2 PCs`
`df_pca$rotation[,1:2]` 

# plot projections
fviz_pca_var(df_pca, col.var="contrib",
  select.var= list(name = c("symmetry_mean","texture_mean","radius_mean","concavity_mean","fractal_dimension_mean")))

# create dataframe with components of interests
df_fit_1 <- data.frame(df_pca$x)
df_fit_1 <- df_fit_1[,1:7] # cover 90% of variance

# compute t-SNE
tsne <- Rtsne(df_fit_1, dims = 2)

## getting the two dimension matrix
tsne_m = data.frame(x = tsne$Y[,1], y = tsne$Y[,2], col = df$diagnosis)  

## plot results from t-SNE
ggplot(tsne_m) +  
  geom_point(aes(x=x, y=y, color=col))+
  ggtitle("t-SNE")`
