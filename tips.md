# Maven

### Build target module
```
mvn -f {{module_name}}
```

# Jersry

### match any path
```
@Path("{any: .*}")
```
```
public Response getSomething(@PathParam("any") List<PathSegment> segments)
```
# IntelliJ

### Change IntelliJ setting
```
vim /Applications/IntelliJ\ IDEA\ CE.app/Contents/bin/idea.properties
```

# MongoDB

### Append new data to array

$push https://docs.mongodb.com/manual/reference/operator/update/push/
```
db.client.update({clientId:"sdk-test-app-2"},{$push:{redirectUri:"mattel://com.mattel.mattelsdk2"}})
```

# Git

### show remote
```
git remote -v
```

### add upstream
```
git remote add taipei_gitlab git@oooo/xxxx.git
```
