# Twitter Data Pipeline using Apache Airflow

## Overview

This project implements a Twitter Data Pipeline using Apache Airflow. The pipeline collects real-time Twitter data based on specific keywords and stores it in a data warehouse for further analysis.

### Features

- **Twitter API Integration**: Connects to the Twitter API using Tweepy to fetch real-time tweets.
- **Data Storage**: Stores collected tweets in a data warehouse (e.g., PostgreSQL, MySQL, or any other supported by Airflow).
- **Scheduling**: Utilizes Airflow DAGs to schedule and automate the data collection process.
- **Customizable**: Easily adaptable to different keywords, storage solutions, and processing requirements.

## Prerequisites

Make sure you have the following installed:

- [Apache Airflow](https://airflow.apache.org/) (Follow the installation guide on their website)
- [Python](https://www.python.org/) (Version 3.x)
- [Tweepy](https://www.tweepy.org/) (Install via `pip install tweepy`)


## Usage

1. Access the Airflow web UI.

2. Navigate to the "DAGs" section and enable the `twitter_data_dag`.

3. Trigger the DAG to start the Twitter data collection process.

4. Monitor the progress and check the logs for any issues.

