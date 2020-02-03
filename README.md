mod_doc Application

Build Command:
```
cd mta_mod_doc ; mkdir -p target ; mbt build -p=cf -t=target --mtar=mta_mod_doc.mtar
```

Deploy Command:
```
cf deploy target/mta_mod_doc.mtar -f
```

UnDeploy Command:
```
cf undeploy mod_doc -f --delete-services
```
