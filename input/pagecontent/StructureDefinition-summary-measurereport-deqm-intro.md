
{% assign id = {{page.id}} %}




### Mandatory Data Elements and Terminology

The following data-elements are mandatory (i.e data MUST be present).

**Each {{site.data.structuredefinitions.[id].type}} must have:**

1. A status
1. A measure report type hardcoded to "summary"
1. The reference to the [Measure]
1. The date the report was generated
1. The organization that reported the data
1. The measurement period
1. The results of the calculation (the Measure Scores)

Each {{site.data.structuredefinitions.[id].type}} *should* have ([Must Support]):

1. Measure results for each group with separate subgroup calculations (stratifiers)
1. Indicate whether improvement in the measure is noted by an increase or decrease in the measure score.
1. The scoring type defined by the referenced Measure using the DEQM [Measure Scoring] Extension
1. Reference to a reporting vendor using the DEQM [Reporting Vendor] Extension
1. A certification identifier using the DEQM [Certification Identifier] Extension
1. Ability to use other types for measure score using the DEQM [Alternate Score Type] Extension
1. Reference to a reporting group using the DEQM [Reporting Group] Extension
1. Specify the software systems used by the reporting system using the CQFM [Software System]({{site.data.fhir.cqfm}}StructureDefinition-cqfm-softwaresystem.html) Extension

**Additional Profile specific implementation guidance:**

{% include report-sd-imp-guidance.md %}

### Examples

{% include summary-measurereports.md %}

{% include link-list.md %}
