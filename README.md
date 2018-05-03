# misc
`trimpcap_install` - Use to install TrimPCAP (and it's dependencies) and set up a series of cron jobs to trim PCAPs recorded by Security Onion after a defined period.   

Default cron job trims PCAPs as follows:

- Older than `3` days: Trim to `1MB` per flow   
- Older than `6` days: Trim to `102KB` per flow   
- Older than `30` days: Trim to `10KB` per flow   

See the following for more information about TrimPCAP:   
http://www.netresec.com/?page=Blog&month=2017-12&post=Don%27t-Delete-PCAP-Files---Trim-Them
