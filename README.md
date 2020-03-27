# README.txt

# TA-GetNetAdaptor
### Description
Executes a powershell script to pull in the interface status of the server. 

### Installation/Platform
Splunk 8.0.2 tested
Windows 2016 x64 tested

1) Create an index
2) Set index on inputs.conf
3) Set interval you want to collect in inputs.conf
4) Tune Timezone another elements as needed in props.conf
5) Install on Universal Forwarders, restart
6) Install on Heavy Forwarders, restart.
7) Install on Indexers, restart. 
8) Install on search heads, restart

### Usage
New new tags or eventtypes are added. 

### History
3.13.2020.1 - daniel, 1.0.0 initial version

### Credits
Daniel Wilson <daniel.p.wilson@live.com>

### License
None

### TO DO/BUGS
1) Add visualizations and a way to compare interfaces.
