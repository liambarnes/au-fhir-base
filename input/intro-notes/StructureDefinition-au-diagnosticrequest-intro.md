#### Usage Notes
The procedure-targetBodyStructure extension should only be used if not implicit in the code found in ServiceRequest.code. If the use case requires bodySite to be handled as a separate resource instead of an inline coded element (e.g. to identify and track separately) then use the standard extension [procedure-targetBodyStructure](http://hl7.org/fhir/R4/extension-procedure-targetbodystructure.html). 

A pathology order is preferred to be a member of the [RCPA - SPIA Requesting Pathology Terminology Reference Set](https://www.rcpa.edu.au/fhir/ValueSet/spia-requesting-refset-3) [<sup>[1]</sup>](https://www.healthterminologies.gov.au/integration/R4/fhir/ValueSet/spia-requesting-refset-3). 

An imaging order is preferred to be a member of the [Imaging Procedure](https://healthterminologies.gov.au/fhir/ValueSet/imaging-procedure-1) value set.

**Extensions under consideration:**
* ServiceRequest: [Result Copies To](StructureDefinition-result-copies-to.html) 