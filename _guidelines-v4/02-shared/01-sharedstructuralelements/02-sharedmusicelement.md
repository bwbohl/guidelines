---
sectionid: sharedMusicElement
title: "General Music Structure Elements"
version: "v4"
---

As indicated above, the general place for encoding the musical text is the {% include link elem="music" %} element. MEI.shared offers two possible child elements:

{% include desc elem="body" %}
{% include desc elem="group" %}

While {% include link elem="body" %} holds the contents of a single musical text, {% include link elem="group" %} allows the textual body to consists of a series of subordinate musical texts or other e.g. to represent a collection of independent musical texts which is to be regarded as a single unit for processing or other purposes. It is provided to simplify the encoding of collections, anthologies, and cyclic works. It can also be used to record the potentially complex internal structure of corpora, covered more fully in chapter {% include link id="corpus" %}. Whether the musical text being encoded should be structured one way or the other is not to be decided here. For example, a collection of songs might be regarded as a single item in some circumstances, or as a number of distinct items in others. In such borderline cases, the encoder must choose whether to treat the text as unitary or composite; each option may have advantages and disadvantages.

There are several more possible child elements of the {% include link elem="music" %} element defined in other modules of MEI, such as {% include link elem="front" %} and {% include link elem="back" %} elements (defined in MEI.text module, cf. {% include link id="text" %}), {% include link elem="performance" %} (defined in MEI.performance module, cf. {% include link id="performances" %}), {% include link elem="genDesc" %} (defined in MEI.genetic module, cf. {% include link id="genetic" %}), {% include link elem="facsimile" %} (defined in MEI.facsimile module, cf. {% include link id="facsimiles" %}).

The overall structure of a single musical text is:

{% include mei example="shared/shared-sample000.xml" valid="" %}

The top-level structure of a composite musical text made up of two unitary musical texts is:

{% include mei example="shared/shared-sample001.xml" valid="" %}
