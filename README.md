# loanDefaultPredictor
Process:
* Cleaned data:
  * Data timeline
  * Created relevant columns
  * Dropped redundant columns
  * Reassessed column dtypes
  * Handled missing data
  * Converted relevant strings to date_time
  * Converted relevant strings to numeric
  * Extract number from strings

Feature Engineering
* Goal:
  * columns in optimal format
  * create bins 
    * continuous -> categorical
  * create new features
  * normalise continuous variables
* Outliers:
  * Binning:
    * Check outliers
    * Include extreme values without skewing data
* Combine features
* MinMax Scaling
  * bring continuous variables  into the same range
* Dummy variables
  * One hot encoding 
* Evaluation Metrics
  * confusion matrix
  * roc curve
   
