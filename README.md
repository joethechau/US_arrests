# US Arrest Analysis with PCA and Regression – R

<p><strong>Performed Principal Component Analysis on US crime data and used principal components to model GDP.</strong></p>
<ul>
  <li>Used <code>prcomp()</code> to conduct PCA on USArrests dataset (Murder, Assault, UrbanPop, Rape), with scaling and centering.</li>
  <li>Retained 86.75% of the total variance using the first two components (PC1 = 62.01%, PC2 = 24.74%).</li>
  <li>Created scree plot and biplot to visualize variance distribution and loading vectors.</li>
  <li>Interpreted PC1 as a measure of overall crime severity; high-crime states like Florida, Nevada, and California had low PC1 scores.</li>
  <li>Added PC1 and PC2 scores to the dataset and performed multiple linear regression using them to predict GDP.</li>
  <li>Found both PC1 (p = 0.00652) and PC2 (p = 0.0265) to be significant predictors at the 5% level.</li>
  <li>Demonstrated how dimensionality reduction via PCA can improve multicollinearity and interpretability in regression modeling.</li>
</ul>

