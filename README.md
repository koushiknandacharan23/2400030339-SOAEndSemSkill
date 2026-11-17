# MockMvcDemo

A complete Spring Boot Maven project for testing a controller endpoint with MockMvc.

## Requirements
- JDK 21
- Spring Tool Suite 4
- Maven (STS includes Maven integration)

## Import into Spring Tool Suite
1. Extract the ZIP file.
2. Open STS.
3. Select File -> Import -> Maven -> Existing Maven Projects.
4. Browse to the extracted `MockMvcDemo` folder.
5. Select `pom.xml` and click Finish.
6. Wait for Maven dependencies to download.

## Run the test
1. Open `src/test/java/com/example/demo/MS1ControllerTest.java`.
2. Right-click the file.
3. Select Run As -> JUnit Test.
4. Expected result: 1 test, 0 failures, 0 errors.

The test simulates:
GET /ms1/add?a=5&b=10

Expected HTTP status: 200 OK
Expected response body: MS 1.1 - Addition = 15

Note: MockMvc performs the test without starting an embedded web server.
