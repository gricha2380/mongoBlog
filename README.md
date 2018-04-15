
# mongoBlog 


## How To use db seed file
```
# Start mongo daemon
mongod
# open the mongo shell
mongo
# switch to your db, for example  "mongoBlog"
> use mongoBlog
# load the seed.js file
> load('./dbseed/seed.js')
# check out the data you have!
> db.getCollectionNames()
```
## Credits
Starter concept from Treehouse 
Dummy text from DuneIpsum: https://github.com/blackwright/dune-ipsum