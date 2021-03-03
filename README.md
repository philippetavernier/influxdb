# influxdb


## with CURL

´´´   curl --request POST "http://localhost:8086/api/v2/write?bucket=bucket-name&org=org-name" --header "Authorization: Token token-key" \
 --data-raw "temperature_in_room,room=kitchen temp=24.2"´´´
