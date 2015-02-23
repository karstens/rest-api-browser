# REST API Asset Browse

An asset browser based on the REST API at /api.json

## Getting started

Start an AEM 6.1 instance at `http://localhost:4502`

Run the following commands:

    # install grunt command (if not yet installed)
    npm install -g grunt-cli
    
    # install all required dependencies
    npm install
    
    # run the app on a grunt's built-in server
    grunt serve
    
A browser should automatically open, showing `http://localhost:9000/#/browser/assets`

The grunt server proxies the requests to the AEM instance and automatically logs in using
the default credentials `admin:admin`.
    

