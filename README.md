# sarcasm_english_spanish.csv
translate sarcasm_english_spanish

Libraries:

pandas → Handle CSV file operations
transformers pipeline → Predefined function to load Helsinki model on Colab

Text Preprocessing:

Remove extra spaces and special characters
Handle empty/null values safely
Prepare clean text for translation

Batch Processing:

Read CSV file into dataframe
Split text into manageable batches (50 rows each)
Translate each batch from English to Spanish
Track and display progress percentage
Combine all translated batches
Add Spanish translation as new column
Save final dataframe with selected columns

