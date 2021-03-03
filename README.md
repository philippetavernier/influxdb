# influxdb

## Install
```
wget https://dl.influxdata.com/influxdb/releases/influxdb2_2.0.3_amd64.deb
sudo dpkg -i influxdb2_2.0.3_amd64.deb
```
## prerequisite
```
sudo apt-get install python3
sudo apt-get install python3-pip
```

## Send Data
### with CURL
```
  curl --request POST "http://localhost:8086/api/v2/write?bucket=bucket-name&org=org-name" --header "Authorization: Token token-key" \
 --data-raw "YOUR DATA"
```
