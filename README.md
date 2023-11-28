# deep-learning-challenge

# Overview
I received a CSV from Alphabet Soup that contains 34,000 companies that were given funding.
This Binary Classifier predicts whether a company will be successful if funded by Alphabet Soup.

# Results
## Data Preprocessing
  The variable target for the model was whether or not the company was successful.
  The featured variables included Company Status, Application Types, Use Cases, Affiliation, Classification, Income Amount, Special Considerations and Ask Amount and   Organization.
  I originally removed the EIN column and Name column as these factors would not be significant in processing the data.
  I later removed the Income Amount, Special Considerations and Ask Amount Columns in hopes of icreasing the accuracy of the model.

## Compiling, Training and Evaluation of the Model
  I trialed between 2 layers and 3 layers as well as trialing various node quantities within those layers. I found that 3 layers with 80, 80, and 20 hidden nodes     and 39 features gave the highest accuracy I reached at 72.839%.

# Summary
  The model overall was not the most accurate. Potential ways to improve this model would be to include more layers with more varying quantities of nodes. A different activation other than sigmoid and relu may be beneficial.
