# maven-libs

Update minor/patch library and Java versions in pom.xml using renovate.

Library versions should not update to unstable versions like rc*.

Currently there is an issue with renovate that updates com/google/protobuf:protobuf-java to 3.20.1 which is an rc version.
