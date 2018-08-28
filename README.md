# hadoop
hadoop core site codes
hi myself Atul.
the code that is to be written in core site file of both master and slave.
here i assumed ip 192.168.43.186 is ip of master 

<?xml version="1.0"?>
<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>

<!-- Put site-specific property overrides in this file. -->

<configuration>

<property>
<name>fs.default.name</name>
<value>hdfs://192.168.43.186:9001</value>
</property>
</configuration>
