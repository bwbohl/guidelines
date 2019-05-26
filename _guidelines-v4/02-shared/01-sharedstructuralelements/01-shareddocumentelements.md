---
sectionid: sharedDocumentElements
title: "Document Root Elements"
version: "v4"
---

MEI defines the following elements qualifying as root elements (i.e. the element containing everything else) of an MEI document:

{% include desc elem="mei" %}
{% include desc atts="att.meiVersion/meiversion" %}
{% include desc elem="meiCorpus" %}
{% include desc elem="meiHead" %}
{% include desc elem="music" %}

The most straightforward – and probably the most common choice fitting most of the usecases when encoding music – is the {% include link elem="mei" %} element. It contains an {% include link elem="meiHead" %} element for capturing metadata and a {% include link elem="music" %} element  for describing the musical text. A more detailed description of the application of {% include link elem="music" %} can be found in the course of this section <?TODO ref ?>. If you want to learn more about the use of the {% include link elem="meiHead" %} element – formally declared in the MEI.header module – please visit the chapter {% include link id="header" %} in the {% include link id="metadata" %} section.

The other potential root elements serve different usecases or purposes.

- a document that contains only metadata, known as an independent or stand-alone header;
- music notation markup without metadata, typically intended to be embedded within another kind of markup, such as TEI.
{% include desc elem="meiCorpus" %} contains an {% include link elem="meiHead" %} element describing a collection of related MEI-encoded texts – known as a corpus – and an {% include link elem="mei" %} element for each text. Further information regarding the organization and encoding of music corpora is given in chapter {% include link id="corpus" %}.


Inclusion of MEI encodings (partial or complete) inside Text Encoding Initiative (TEI) documents is covered in the TEI Guidelines at [http://www.tei-c.org/release/doc/tei-p5-doc/en/html/FT.html#FTNM](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/FT.html#FTNM){:.link_ref} and by the TEI Music Special Interest Group at [http://www.tei-c.org/SIG/Music/twm/index.html](http://www.tei-c.org/SIG/Music/twm/index.html){:.link_ref}.
