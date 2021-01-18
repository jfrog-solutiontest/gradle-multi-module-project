`
./gradlew wrapper --gradle-version 6.7 --distribution-type bin
`

`
clean publish -PbintrayUsername=bintrayUsername -PbintrayPassword=bintrayAPIKey -Pversion=versionToBeDeployed -PapiBintrayUrl=api.bintray.com/api.bintray.net
`