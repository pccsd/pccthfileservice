UPDATE : 28/09/2022
By : Kangwan .T
JDK 11 MAVEN 3.8.3


Build and Run
mvn clean install
mvn spring-boot:run

TEST METHOD  : POSTMAN
see picture > /TestMethod Folder 

http://localhost:8080/file/upload
Method : POST
body : form-data
key : files > select flies

http://localhost:8080/file/download/{Filename.extension}
Method : GET

PATH Default : Edit FileResource.java >  public static final String DIRECTORY 
eg. /Downloads/uploads/