
# LEED PREDICTION
## ABOUT

This project focuses on developing a deep learning model to predict the likelihood of a lead converting to a customer
based on their activity logs. The data is extracted from a PostgreSQLdatabase, where activity logs are organized and
processed using SQL queries to create viewsand pivot tables. These tables provide a structured format for the log events
associated with various projects, capturing the timestamps and frequencies of specific actions like questionnaire and 
proposal activities.

The model is built using TensorFlow and Keras, incorporating a sequential architecture with layers designed for efficient 
feature extraction and prediction. The data is preprocessed, normalized, and then used to train the model. Once trained,
the model's performance is evaluated on key metrics such as accuracy and loss. This predictive model assists in identifying
high-potential leads, thereby aiding in strategic decision-making and resource allocation in customer acquisition efforts.

## TOOLS
### Python Libraries
pandas, numpy, matplotlib, tensorflow & keras, sklearn (scikit-learn)
### Database Connection
psycopg2
### SQL
Used to execute queries for creating views and pivot tables within the PostgreSQL database, organizing the activity log data for further analysis.
