# README

## Generating the SDK

```
java -jar modules/openapi-generator-cli/target/openapi-generator-cli.jar generate \
  -i http://localhost:8080/api/v1/swagger.json \
  -l android \
  -o ~/dev/android/c3s-sdk
```

```
cd c3d-sdk
mvn clean package
```

Using the Openapi-Generator (or Swagger-codegen generator), point it to your local install of the backend (or a local copy of the swagger file) and run it.

Copy the `jar` file (in the `target` directory in to the `libs` folder of your app and update your `build.gradle`. Easy?!?

##
