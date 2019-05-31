---
sectionid: sharedMusicElement
title: "General Music Structure Elements"
version: "v4"
---

MEI texts may be regarded either as unitary; that is, forming an organic whole, or as composite; that is, consisting of several components which are in some important sense independent of each other. The distinction is not always entirely obvious. For example, a collection of songs might be regarded as a single item in some circumstances, or as a number of distinct items in others. In such borderline cases, the encoder must choose whether to treat the text as unitary or composite; each option may have advantages and disadvantages.

Whether unitary or composite, the musical text is marked with the {% include link elem="music" %} tag and may contain front matter, a body, and back matter. In unitary texts, the body is tagged using the {% include link elem="body" %} element; in composite texts, however, where the textual body consists of a series of subordinate musical texts or other groups, it is tagged with the {% include link elem="group" %} element. The overall structure of any musical text, unitary or composite, is thus defined by the following elements:

{% include desc elem="body" %}
{% include desc elem="group" %}


There are several more possible child elements of the {% include link elem="music" %} element defined in other modules of MEI, such as {% include link elem="front" %} and {% include link elem="back" %} elements (defined in MEI.text module, cf. {% include link id="text" %}), {% include link elem="performance" %} (defined in MEI.performance module, cf. {% include link id="performances" %}), {% include link elem="genDesc" %} (defined in MEI.genetic module, cf. {% include link id="genetic" %}), {% include link elem="facsimile" %} (defined in MEI.facsimile module, cf. {% include link id="facsimiles" %}).

The overall structure of a single musical text is:

{% include mei example="shared/shared-sample000.xml" valid="" %}

The top-level structure of a composite musical text made up of two unitary musical texts is:

{% include mei example="shared/shared-sample001.xml" valid="" %}
