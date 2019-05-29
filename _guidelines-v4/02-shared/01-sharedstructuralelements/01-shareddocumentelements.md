---
sectionid: sharedDocumentElements
title: "Document Root Elements"
version: "v4"
---

MEI defines the following elements qualifying as root elements (i.e. the element containing everything else) of an MEI document:

{% include desc elem="mei" %}
{% include desc elem="meiCorpus" %}
{% include desc elem="meiHead" %}
{% include desc elem="music" %}

The most straightforward – and probably the most common choice fitting most of the usecases when encoding music – is the {% include link elem="mei" %} element. It contains an {% include link elem="meiHead" %} element for capturing metadata and a {% include link elem="music" %} element  for describing the musical text. A more detailed description of the application of {% include link elem="music" %} can be found in the course of this section <?TODO ref ?>. If you want to learn more about the use of the {% include link elem="meiHead" %} element – formally declared in the MEI.header module – please visit the chapter {% include link id="header" %} in the {% include link id="metadata" %} section.

The below example shows the basic structure of an MEI file with {% include link elem="mei" %} as root element. Please be aware that this example still does not represent a valid MEI file:

{% include mei example="shared/shared-sample0000.xml" valid="no" %}

The other potential root elements serve different usecases or purposes.

{% include desc elem="meiCorpus" %} contains an {% include link elem="meiHead" %} element describing a collection of related MEI-encoded texts – known as a corpus – and an {% include link elem="mei" %} element for each text. Further information regarding the organization and encoding of music corpora is given in chapter {% include link id="corpus" %}.

The below example shows the basic structure of an MEI file with {% include link elem="meiCorpus" %} as root element. Please be aware that this example still does not represent a valid MEI file:

{% include mei example="shared/shared-sample0001.xml" valid="no" %}

A document with {% include desc elem="meiHead" %} as root element only contains metadata and is also known as an independent or stand-alone header. Stand-alone headers are more fully described in chapter {% include link id="headerIndependentHeader" %}.

The below example shows the basic structure of an MEI file with {% include link elem="meiHead" %} as root element. Please be aware that this example still does not represent a valid MEI file:

{% include mei example="shared/shared-sample0002.xml" valid="no" %}

While a document with {% include link elem="music" %} as root element provides music notation markup without metadata, and could serve ebedding MEI within another kind of markup, e.g. TEI (see {% include link id ="tei" %}).

{% include desc atts="att.meiVersion/meiversion" %}

In all of the above cases the {% include link att="meiversion" %} attribute – although not required – is crucial for defining a stable referece to the MEI-version used in the enclosed encoding.

