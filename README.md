# spark-dataproc
 Create Spark Job and Bash script to run dataproc workflow-templates

# Description
As data is needed everyday by all related departments, data engineers need to not only manage the data but also provide it continuously. One of the available option is to process the data by using <a href="https://spark.apache.org/">Apache Spark</a> on top of <a href="https://cloud.google.com/dataproc"> Google Cloud dataproc</a>, and using <a href="https://cloud.google.com/bigquery">Google BigQuery</a> to act as a Data Warehouse.

# Prerequisites
- List of requirements are available in the `requirements.txt` and can be installed by running `pip install -r requirements.txt`

# Data
The example of JSON file is available in the `resources` folder with the name of `2021-04-27-example.json`.

The data looks like the following (with the actual data has more that 5000 rows):

```
{
  "flight_date": "2021-04-27",
  "airline_code": "19805",
  "flight_num": 1,
  "source_airport": "JFK",
  "destination_airport": "LAX",
  "departure_time": 854,
  "departure_delay": -6,
  "arrival_time": 1217,
  "arrival_delay": 2,
  "airtime": 355,
  "distance": 2475,
  "id": 1
}
{
  "flight_date": "2021-04-27",
  "airline_code": "19805",
  "flight_num": 1,
  "source_airport": "JFK",
  "destination_airport": "LAX",
  "departure_time": 854,
  "departure_delay": -6,
  "arrival_time": 1217,
  "arrival_delay": 2,
  "airtime": 355,
  "distance": 2475,
  "id": 1
}
```

# Flow
![Alt text](img/flow.jpg?raw=true "spark-dataproc")
- Create Spark Job
- Create workflow-templates
- View output and log

# Running the Program
- (WORK IN PROGRESS)

# Output
- (WORK IN PROGRESS)

# Notes
- 
- This code is made as a Week 3 Task in the Academi by blank-space Data Engineering Track Program (https://www.blank-space.io/program)

# Contact
For further information, you might want to reach me to ricky.nauvaldy@gmail.com