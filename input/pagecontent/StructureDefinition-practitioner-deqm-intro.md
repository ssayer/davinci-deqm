
{% assign id = {{page.id}} %}




### Mandatory Data Elements and Terminology

The following data-elements are mandatory (i.e data MUST be present).

**Each {{site.data.structuredefinitions.[id].type}} must have:**

1. Either a National Provider Identifier (NPI), or CMS Certification Number(CCN) identifier

<!--

Each {{site.data.structuredefinitions.[id].type}} *should* have ([Must Support](guidance.html#must-support)):

1. The beneficiary

-->

**Additional Profile specific implementation guidance:**

The "Full View" tab below displays all the identifier slices including the *CCN* slice defined in this guide and *NPI* slice which is inherited indirectly from the [US Core Practitioner Profile].

### Examples

{% include list-simple-practitioners.xhtml %}

{% include link-list.md %}
