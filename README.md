# wsdl-server

**Build and run project**
./mvnw clean install -DskipTests
./mvnw spring-boot:run

**Request for server test:**
curl --header "content-type:text/xml" -d @request.xml http://localhost:8080/ws