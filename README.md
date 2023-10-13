# mortgage-loan
Background

Banks can monitor the status of the loan disbursements with Watsonx.data. Data could be stored in different formats both semi structured and structured. The Watsonx.data presto engine can run federated queries across data in different forms and help analyze the data. Given a large bank can create large volumes of data, they can always move the older data to other cheaper storage formats while still allowing data to be queried along with the new data that is stored in more expensive block storage. E.g. loan disbursement details of customer – data more than 3 years can be moved to commodity storage and still be queried with standard ANSI SQL queries with a better price to performance.

The use-case is about a retail bank having customer data stored in its relational databases like DB2 and having data on customer feedback for example getting stored on .csv files that are stored on commodity hardware. Data aggregation can be done between data in csv and well as relational tables. Old loan disbursement data can be copied over to cheaper storage with a simple command as illustrated.



