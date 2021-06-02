'To make predictions on a new predictor column matrix, X, use: 
  yfit = c.predictFcn(X) 
replacing ''c'' with the name of the variable that is this struct, e.g. ''trainedModel''. 
 
X must contain exactly 11 columns because this model was trained using 11 predictors. 
X must contain only predictor columns in exactly the same order and format as your training 
data. Do not include the response column or any columns you did not import into the app. 
 
For more information, see <a href="matlab:helpview(fullfile(docroot, ''stats'', ''stats.map''), ''appregression_exportmodeltoworkspace'')">How to predict using an exported model</a>.'