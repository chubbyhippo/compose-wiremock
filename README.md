```
keytool -genkey -alias wiremock -keyalg RSA -validity 3650 -keystore wiremock/wiremock.p12 -storetype PKCS12 -storepass password -keypass password -dname "CN=localhost, OU=ID, O=Unknown, L=Unknown, S=Unknown, C=Unknown"
```