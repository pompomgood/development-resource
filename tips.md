# Maven

### Build target module
```
mvn -f {{module_name}}
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
