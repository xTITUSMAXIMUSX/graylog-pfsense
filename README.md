# graylog-pfsense Extractor
This extractor is built for pfSense `24.11` and Graylog `6.1.3`

# Usage
Note: You need to use this with the `syslog RFC 5424 with RFC 3339` set on your pfSense

1. Naviagte to `System`>`Inputs`
2. Find your input you use for pfSense
3. Click on `Manage extractors`
4. Click on Actions at the top right of the screen and click `Import extractors`
5. Copy and paste the `extrators.json` contents into the field
6. Click on `Add extractors to input`
