A music streaming startup, Sparkify, has grown their user base and song database even more and want to move their data warehouse to a data lake. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app

The purpose of this project is to build an ETL pipeline that extracts their data from S3, processes them using Spark, and loads the data back into S3 as a set of dimensional tables. This will allow their analytics team to continue finding insights in what songs their users are listening to.

Project Datasets
You'll be working with two datasets that reside in S3. Here are the S3 links for each:
Song data: `s3://udacity-dend/song_data`
Log data: `s3://udacity-dend/log_data`

