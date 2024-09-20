# FHIR Examples Dataset

## Overview
* Dataset generated from https://github.com/google/fhir-examples using Synthea
* Data uploaded to a HAPI FHIR server (generating new numerical IDs)
* Generated IPS using $summary command on HAPI FHIR https://hapifhir.io/hapi-fhir/docs/server_jpa/ips.html
* Created super simple IPS markdown representation only containing patient sex, age, allergies, medications and conditions


# Directory structure

| Directory    | File naming convention | Description                                                                                                                    |
|--------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| fhir-bundles | $ID-bundle.json        | original bundles created from the fhir-examples project                                                                        |
| ips-fhir     | $ID-ips.json           | generated IPS files. Note that the only the top level composition contains the narrative (HTML representation in text element) |
| ips-markdown | $ID-ips.md             | super simple markdown version                                                                                                  |


