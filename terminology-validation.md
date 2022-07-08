# Terminology validation via GitHub actions

This page records automated testing of external CodeSystems loaded into the package [fhir.tx.support.r4](http://fhir.org/packages/fhir.tx.support.r4/)

The operation used to validate these resources is found on the core spec pages:
* [Operation $expand on ValueSet](http://hl7.org/fhir/valueset-operation-expand.html)
* [Operation $validate-code on ValueSet](http://hl7.org/fhir/valueset-operation-validate-code.html)

## CodeSystem: Australian Immunisation Register Vaccine

Original source on NCTS: https://www.humanservices.gov.au/organisations/health-professionals/enablers/air-vaccine-code-formats

Found on tx.fhir.org here: https://tx.fhir.org/r4/CodeSystem/australian-immunisation-register-vaccine-20210222

### Testing
[![Programmatically expand 'Australian Immunisation Register Vaccine' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-expand.yml/badge.svg?branch=fhir.tx.support.r4-validation)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-expand.yml)


## CodeSystem: NCTIS Data Components

Original source on NCTS: https://healthterminologies.gov.au/fhir/CodeSystem/nctis-data-components-1

Yet to be loaded into tx.fhir.org 

### Testing

[![Programmatically expand 'NCTIS Data Components' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-ndc-expand.yml/badge.svg?branch=fhir.tx.support.r4-validation)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-ndc-expand.yml)

