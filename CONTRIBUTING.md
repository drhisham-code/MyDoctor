# How to become a contributor and submit your own code

## Contributor License Agreements

We'd love to accept your patches! Before we can take them, we
want you to accept our policy: **By submitting a pull request, you 
present that you have the right to license your contribution to 
MyDoctor and its community, and agree by submitting the patch 
that your contributions are licensed under the MIT license.**

## Contributing A Patch

1. Submit an issue describing your proposed change to the repo in question.
1. The repo owner will respond to your issue promptly.
1. Fork the desired repo, develop and test your code changes.
1. Ensure that your code adheres to the existing style in the sample to which
   you are contributing. Refer to the
   [Python Style Guide]
   (https://google.github.io/styleguide/pyguide.html) for the
   recommended coding standards for this organization.
1. Ensure that your code has an appropriate set of unit tests which all pass.
1. Submit a pull request.

## Potential Features, Ideas, Goals
1. Bridge Google Calendar API and FHIR(Fast Healthcare Interoperability Resources) API to schedule doctor appointments when both patient and doctor are available during work hours
   1. https://developers.google.com/api-client-library/python/
   1. https://www.hl7.org/fhir/overview.html
1. Integrate actual patient and doctor contact info (eg email, phone numbers) into app
1. Migrate host to Microsoft Azure or Google Firebase
   
## Bug Fixing
1. Alexa does not always understand what we say
1. Alexa sometimes interprets wrong symptom (eg. Alexa once thought rashes == third degree burns on 50% of the body)
