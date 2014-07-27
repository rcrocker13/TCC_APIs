Requirements: 

For automatic data source upload & publishing to occur:

- Node app must be run on Windows or Linux (as we use the TDE API, which doesn't exist on the MAC)
- The Python-based TDE API must be installed on the machine 
- Python 2.7.X must be installed on the same machine
- The node app should be installed to c:\node (don't forget to do an npm install)
- The script will look for uploaded files in C:\node\public\uploads

In order for the /Analyze page to property list data sources on your server:

- Make sure you've updated the admin.username and admin.password values to your credentials
- Update the tableauServer variable to point to your server
- In function getDataSources(), you must update the hard-coded SiteID to a site on your server.

