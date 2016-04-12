# ripe-atlas-to-gelf
RIPE Atlas to GELF with Python

## Prototype of a RIPE Atlas to GELF parser

Usage: python measurements-to-gelf.py (measurement id) (timeframe in min)

Example: python measurements-to-gelf.py 12323 5

Please define Server and Port inside the script and you need an API Key for Geolocation from https://geocoder.opencagedata.com/pricing

### As a cronjob
*/5 * * * * /usr/bin/python measurements-to-gelf.py 12323 8
