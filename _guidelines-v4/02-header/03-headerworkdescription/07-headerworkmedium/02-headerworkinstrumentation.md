---
sectionid: headerWorkInstrumentation
title: "Instrumentation"
version: "v3"
---

The {% include link elem="perfreslist" %} element is used to capture the solo and ensemble
instrumental and vocal resources of a composition. For example, a work for a standard
ensemble may be indicated thus:

{% include plainExample.html example="examples/header/header-sample057.xml" valid="true" version=page.version %}
The detailed make-up of standard and non-standard ensembles may also be enumerated:

{% include plainExample.html example="examples/header/header-sample058.xml" valid="true" version=page.version %}
Where multiple instruments of the same kind are used, the **@count** attribute on
{% include link elem="perfres" %} may be used to encode the exact number of players called
for.

{% include plainExample.html example="examples/header/header-sample059.xml" valid="true" version=page.version %}
Instrument or voice specifications may be grouped using the {% include link elem="perfreslist" %} element and a label assigned to the group with {% include link elem="head" %}. For example:

{% include plainExample.html example="examples/header/header-sample060.xml" valid="true" version=page.version %}
{% include plainExample.html example="examples/header/header-sample061.xml" valid="true" version=page.version %}
The preceding example also demonstrates how instrumental doublings can be accommodate
through the use of nested {% include link elem="perfres" %} elements. Only the outer-most
perfRes element should use the **@count** attribute. Its value should reflect the
total number of performers, not the number of instruments played.

The {% include link elem="perfres" %} element provides the **@codedval** attribute,
which can be used to record a coded value that represents the string value stored
as the
element's content. It is recommended that coded values be taken from a standardized
list,
such as the International Association of Music Libraries' Medium of performance Codes
List
or the MARC Instruments and Voices Code List.

{% include plainExample.html example="examples/header/header-sample062.xml" valid="true" version=page.version %}
Solo parts may be marked with the **@solo** attribute of {% include link elem="perfres" %}, like so:

{% include plainExample.html example="examples/header/header-sample063.xml" valid="true" version=page.version %}
Music for a single player should, however, never use the **@solo** attribute.

{% include plainExample.html example="examples/header/header-sample064.xml" valid="true" version=page.version %}

