# event-list
website which lists events using the events-all API from instiapp. das it 
Hosted on the web-others container in the events folder, make sure the html file is named index.html, thats it (no need to restart container)
In case you shift the website elsewhere make sure that the new IP/domain is there in the CORS whitelist of instiapp-api (settings_prod.py)