# Terminology validation via GitHub actions

This page records automated testing of external CodeSystems loaded into the package [fhir.tx.support.r4](http://fhir.org/packages/fhir.tx.support.r4/)

The operations used to validate these resources is found on the core spec pages:
* [Operation $expand on ValueSet](http://hl7.org/fhir/valueset-operation-expand.html)
* [Operation $validate-code on ValueSet](http://hl7.org/fhir/valueset-operation-validate-code.html)

## CodeSystem: Australian Immunisation Register Vaccine

Original source on NCTS: https://www.healthterminologies.gov.au/integration/R4/fhir/CodeSystem/australian-immunisation-register-vaccine-20210222

Mirrored on tx.fhir.org here: https://tx.fhir.org/r4/CodeSystem/australian-immunisation-register-vaccine-20210222 (v20210222 - noting later [20220207](https://www.healthterminologies.gov.au/integration/R4/fhir/CodeSystem/australian-immunisation-register-vaccine-20220207) is available )

### Testing
[![ValueSet $expand on 'Australian Immunisation Register Vaccine' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-expand.yml/badge.svg?branch=fhir.tx.support.r4-validation)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-expand.yml)

[![ValueSet $validate-code an existing code in 'Australian Immunisation Register Vaccine' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-validate-code-pass.yml/badge.svg)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-validate-code-pass.yml)

[![ValueSet $validate-code a non-existing code in 'Australian Immunisation Register Vaccine' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-validate-code-fail.yml/badge.svg)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-air-validate-code-fail.yml)

## CodeSystem: NCTIS Data Components

Original source on NCTS: https://healthterminologies.gov.au/fhir/CodeSystem/nctis-data-components-1

Yet to be loaded into tx.fhir.org 

### Testing

[![ValueSet $expand on 'NCTIS Data Components' CodeSystem](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-ndc-expand.yml/badge.svg?branch=fhir.tx.support.r4-validation)](https://github.com/robeastwood-agency/test-fhir-ig/actions/workflows/valueset-ndc-expand.yml)

