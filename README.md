# Salesforce Data Cloud Predition Model Project

Using Quote Line Item data from CRM , a prediction model is trained to predict the sales price.

# Implementation Steps

1 - Ingesting CRM data - Quote Line Items
2 - Creating a custom Data Model Object for Quote Line Item (no default DMO)
3 - Mapping the required fields and fields used in the prediction model
4 - Creating a prediction model and training it on the Quote Line Item DMO (Model Algorithm : Extreme Gradient Boosing)
5 - Using the prediction model to predict sales price of new Quote Line Items.

# Next Steps

1 - Clone this repository locally.
2 - Deploy the metadata to your Org from VS Code or CLI
3 - Navigate to 'data kits' in setup and deploy the data kit.
4 - Ingest your CRM data  ( Quote Line Items ) -  Refresh the stream
5 - Retrain the model if needed
6 - From a flow, call the action associated with the model to pass the input parameters and generate prediction and display the prediction.
