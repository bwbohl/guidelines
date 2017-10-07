---
sectionid: cmnRestsMultiRest
title: "Multiple-Measure Rests"
---



The [multiRest](/v3/elements/multiRest.html){:.link_odd_elementSpec} (<span class="expan">multiple measure rest</span>) element is
used to encode multiple measures of rest. It is commonly used in performer parts,
but
due to the problem of synchronicity with other staves, it is never found in scores.
A
numeric value, stored in the **@num** attribute, indicates the number of resting
measures. The various visual forms displayed below are not captured by [multiRest](/v3/elements/multiRest.html){:.link_odd_elementSpec}, but may be created by rendering software.


<figure class="figure">
   <img src="../../../../guidelines/3.0.0/Images/ExampleImages/multirest.png" class="img-responsive"></img>
   <figcaption class="figure-caption">Figure 4. Forms of multiple measure rests</figcaption>
</figure>
{% include plainExample.html example="./v3/examples/cmn/cmn-sample102.xml" valid="true" %}
