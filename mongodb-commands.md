# MongoDB

sjbude183v

```shell
$ mongo
> show dbs
> use cda
> show collections
> db.applications_test.find({"isEnabled" : true, "serviceOwner.userId" : "shikapoo"})
> db.applications_test.findOne({'applicationName':'CSIT DevOps Portal'})
```
