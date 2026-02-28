# data-engineering-zoomcamp-module-5-Public
Data Engineering Zoomcamp 2026 - Module 5

Question 1
#.bruin.yml and pipeline/ with pipeline.yml and assets/.

Question 2
#time_interval - incremental based on a time column

Question 3
#bash bruin run --var '{"taxi_types": ["yellow"]}'

Question 4
#bruin run ingestion/trips.py --downstream

Question 5
#columns:
  - name: pickup_datetime
    type: timestamp
    checks:
      - name: not_null
   
Question 6
#bash bruin lineage .

Question 7
#bash bruin run --full-refresh
