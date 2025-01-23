URL = "https://github.com/DataTalksClub/nyc-tlc-data/releases/download/green/green_tripdata_2019-10.csv.gz"

python ingest_taxi_data.py \
	--user=root \
	--password=postgres \
	--host=localhost \
	--port=5432 \
	--db="postgres" \
	--table_name=green_taxi_trips_2019 \
	--url="https://github.com/DataTalksClub/nyc-tlc-data/releases/download/green/green_tripdata_2019-10.csv.gz"