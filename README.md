# data-engineering
End to End data engineering project using aws and snowflake
The project architecture is aws lambda fetchs data from weather api and dumps it into dynamodb and then by making use of dynamodb stream will pass the stream to aws lambda to process the data and it will be loaded into  aws s3. snowflake will take data from s3 and loads in snowflake database
