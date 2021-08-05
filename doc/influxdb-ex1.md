# InfluxDB example 1

## Open InfluxDB web console.

Open web browser and go to your InfluxDB web console. For example, http://localhost:8086/

Start initializing process. If you alreadly have initialized site, please skip it.

## Create bucket and Telegraf configuration

Click "data" icon in side menu.

![01](./images/influxdb/influxdb-quickstart-01.png)

Click "Buckets" tab.

![02](./images/influxdb/influxdb-quickstart-02.png)

Click "+ Create Bucket" button.

![03](./images/influxdb/influxdb-quickstart-03.png)

Type bucket name and click "Create" button. In this example, bucket name is "mytest".

![04](./images/influxdb/influxdb-quickstart-04.png)

New bucket will be created.

![05](./images/influxdb/influxdb-quickstart-05.png)

Click "Telegraf" tab and click "+ Create Configuration" button.

![06](./images/influxdb/influxdb-quickstart-06.png)

"Create Telegraf Configuration" dialog will be opened.

![07](./images/influxdb/influxdb-quickstart-07.png)

Select "Bucket" which had been created for this example.

![08](./images/influxdb/influxdb-quickstart-08.png)

Select "System".

![09](./images/influxdb/influxdb-quickstart-09.png)

Type "Telegraf Configuration Name". For example, "My configuration".

![10](./images/influxdb/influxdb-quickstart-10.png)

The configuration has been finished.

![11](./images/influxdb/influxdb-quickstart-11.png)

Please memo two commands.

![12](./images/influxdb/influxdb-quickstart-12.png)

Telegraf configuration had been created.

![13](./images/influxdb/influxdb-quickstart-13.png)

## Download and run Telegraf

 - Download Telegraf from [here](https://portal.influxdata.com/downloads/)
 - Install or unarchive Telegraf
    - Telegraf is a single binary file without any dependencies.
 - Run the commands you already memoed.

## Explore data

Click "Explore" button in side menu.

![14](./images/influxdb/influxdb-quickstart-14.png)

Select your bucket in "From" tab.

![15](./images/influxdb/influxdb-quickstart-15.png)

Select "cpu" in "Filter" tab and click "Submit" button.

![16](./images/influxdb/influxdb-quickstart-16.png)

You can check CPU usage on Telegraf running machine.

![17](./images/influxdb/influxdb-quickstart-17.png)
