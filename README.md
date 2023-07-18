## Info 
Basic mods to the 4.2 pre-soldered firmware to post to InfluxDB.
You can also uncomment the JSON function block instead to get JSON post for testing.

## Config
Just update the variables:
`APIURL` and `APITOKEN` to your InfluxDB info.
You will also need to update `lineProtocol` to match your system.

**TODO:**
Add a schema for InfluxDB to make this just work OOB.

## Grafana Dashboard
Inside the `grafana-dashboard` folder is a JSON config file as a jumping off point. It should look like this:

![Grafana Dashboard](grafana-dashboard/dash.png?raw=true)

