# Public API Documentation for TD Connect
This is a repo for the public facing API documentation for TD Connect. The documentation uses a markdown language called API Blueprint and is hosted on Apiary. 

We have internal documentation i.e. [Advertiser Management](https://connect.tradedoubler.com/advertiser/api/doc/index.html) but it is documented for each service rather than a full user group (i.e. there is a doc for advertiser report service, user management service, authentication service, all of which are used by an advertiser)

This repo stores the API documentation as a backup to Apiary

### Services
We have the following API services documented:

* [Publisher](https://tradedoubler.docs.apiary.io)
* [Advertiser](https://advertiserwip.docs.apiary.io/)
* [Agency](https://tradedoubleragency.docs.apiary.io/)
* [Agency specific Advertiser documentation](https://tradedoubleragencyadv.docs.apiary.io/)

### Todo:
1. Document Network services
2. Break out master Blueprint file into smaller files to easily maintain
3. Setup Hercule to build master file to upload to Apiary
4. Explore setup - do we use public Apiary server or host our own server that renders API Blueprint to fully brand documentation. Alternatively do we move to another markup that is compatible with our source code