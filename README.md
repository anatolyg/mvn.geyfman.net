# mvn.geyfman.net

my maven repo

## Projects available

1. [org.json.JSON](./releases/org/json/JSON)
2. [org.hl7.fhir](./releases/org/hl7/fhir)

## Publishing instructions

    mvn -DaltDeploymentRepository=snapshot-repo::default::file:/PATH/TO/mvn.geyfman.net/releases clean deploy

