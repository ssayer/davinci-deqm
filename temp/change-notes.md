
The Data Exchange For Quality Measures Implementation Guide was developed under the  [Davinci Project](#)


Changes and Updates for version 0.2.0

1. Applied all resolutions from STU1 Ballot
1. Updated and Expanded the Background Section on the Clinical Quality Measures Ecosystem and how this guide fits into that Ecosystem.
1. Added Guidance on Measure Reporting
1. Added Use Cases for Colorectal Screening and Venous Thromboembolism Prophylaxis Measure Reporting

Changes and Updates for version 1.0.0

1. Applied all resolutions from May STU1 Ballot

Changes and Updates for version 1.1.0

1. Creation of FHIR R4 version.
1. Additional examples

Changes and Updates for version 1.1.1

1. Applied all resolutions from STU2 Ballot

    - Various Technical Corrections and Corrections to Typographical Errors
    - updated examples
    - Add DEQM [Measure Scoring] Extension to the DEQM Individual MeasureReport Profile and DEQM Summary MeasureReport Profile (FHIR-27044)
    - Add [`MeasureReport.improvementNotation`](StructureDefinition-indv-measurereport-deqm-definitions.html#MeasureReport.improvementNotation) to the DEQM Individual MeasureReport Profile and DEQM Summary MeasureReport Profile (FHIR-27044)
    - Add Invariant [deqm-2](StructureDefinition-indv-measurereport-deqm-definitions.html#MeasureReport) to the DEQM Individual MeasureReport Profile and DEQM Summary MeasureReport Profile (FHIR-27044)
    - Add Sections describing snapshot and incremental updates for data exchange for both [Submit Data](datax.html#submit-updates) and [Collect Data](datax.html#collect-updates) transactions (FHIR-26076, FHIR-26092, FHIR-26079)
    - Add [Glossary](index.html#glossary) defining terms used in this implementation guide. (FHIR-26087,FHIR-26076,FHIR-25523)
    - [Guidance](guidance.html#using-contained-resources-in-the-response-transaction) on using contained resources when transacting data (FHIR-26304)
    - Additional [Preconditions and Assumptions](guidance.html#preconditions-and-assumptions) (FHIR-26088, FHIR-26086, FHIR-26075)
    - Change [Practitioner Identifier OID](StructureDefinition-organization-deqm-definitions.html#Organization.identifier:ein) for Tax ID from ITIN to EIN (FHIR-26613, FHIR-26086)
    - Clarify how [much data is needed](indv-reporting.html#how-much-data-should-be-sent) for individual reporting (FHIR-26090)
    - Clarify how [much data is needed](datax.html#data-exchange) for data exchange (FHIR-26083)
    -  Clarify how data consumers [communicate data requirements](datax.html#collect-data ). (FHIR-26084)
    - Clarify [negation pattern](guidance.html#negation-patterns-for-quality-measures) (FHIR-26077)
    - Clarify [usage of correct measure version](datax.html#data-exchange) . (FHIR-26081)
    - Clarify [discovery of data requirements](datax.html#gather-data-requirements-from-consumer)). (FHIR-26085)
    - Clarify [stakeholders](datax.html#data-exchange) (FHIR-26082)
    - Add [reference](index.html#introduction) to Da Vinci Guiding Principles (FHIR-26078)
    - Add [implementer notes](StructureDefinition-indv-measurereport-deqm.html#mandatory-data-elements-and-terminology) to  DEQM Data-Exchange MeasureReport Profile  (FHIR-26073)
    - Add [Practitioner Profile](StructureDefinition-practitioner-deqm.html) to accommodate CMS Certification Number identifier(CCN) and add CCN to [Organization Profile](StructureDefinition-organization-deqm.html) (FHIR-25739)
    - Add [software name/version extension](StructureDefinition-indv-measurereport-deqm-definitions.html#MeasureReport.extension:vendor) to MeasureReport Profiles (FHIR-25721)
    - Add required [`id`](StructureDefinition-summary-measurereport-deqm-definitions.html#MeasureReport.group.population.code) element to the MeasureReport profiles (FHIR-25716)
    - [Document](datax.html#provenance) that $submit-data and $collect-data should support the use of the X-Provenance header (FHIR-25624)
    - A extensions for [software and version](StructureDefinition-datax-measurereport-deqm-definitions.html#MeasureReport.extension:software) (FHIR-25721)
    - Define [default profiles](guidance.html#default-profiles-used-in-the-evaluation-of-a-measure) for this implementation guide (FHIR-27818)
    - Add [`MeasureReport.group.population.count` as 0..1 Must Support](StructureDefinition-indv-measurereport-deqm.html#profile) for individual report profile. (FHIR-27862)


    {% include link-list.md %}
