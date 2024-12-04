## Lesson Management

### Client

### Backend

### Database

AWS DynamoDB for Local Systems: This Database is more like the documentDB or MongoDB that is fully managed by AWS, it's not ideal for tables with many relationships, highly nested data structures with restrictive complex filtering, sorting and aggregation.

- AWS DynamoDB local installation `https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html` but make sure u have JAVA installed on your system.
- Unzip the downloaded files in a location of your choosing
- Run`BOTH` the DynamoDBLocal_lib and DynamoDBLocal.jar within the terminal to start the JVM `java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb`

NOTE: This path config is for MacBooks -> Location for the Library file, JAR file and persistentDB.

```
java -Djava.library.path=/Users/YOUR_USERNAME/Downloads/dynamodb_local/DynamoDBLocal_lib -jar /Users/YOUR_USERNAME/Downloads/dynamodb_local/DynamoDBLocal.jar -sharedDb -dbPath /Users/lawrencejews/Downloads/PersistentDB
```
