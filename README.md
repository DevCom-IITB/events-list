# event-list
website which lists events using the events-all API from instiapp. das it 
Hosted on the web-others container in the events folder, make sure the html file is named index.html, thats it (no need to restart container)
In case you shift the website elsewhere make sure that the new IP/domain is there in the CORS whitelist of instiapp-api (settings_prod.py)

# local-dev
ensure URL port is 5500 and it is localhost not 127.0.0.1 (as CORS whitelist is currently enabled for the former not the latter)