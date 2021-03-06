---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.midi.event"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.midi.event">att.midi.event</h3>
      <div class="specs">
         <div class="desc">Attributes common to MIDI events.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.midi</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Identifies the layer to which a feature applies.">layer</span>, <span class="ident attribute" title="Indicates the part in which the current feature should appear. Use '%all' when the feature should occur in every part.">part</span>, <span class="ident attribute" title="Signifies the part staff on which a notated feature occurs. Use '%all' when the feature should occur on every staff.">partstaff</span>, <span class="ident attribute" title="Signifies the staff on which a notated event occurs or to which a control event applies. Mandatory when applicable.">staff</span>, <span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp</span>, <span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span>, <span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Identifies the layer to which a feature applies.">layer</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Identifies the layer to which a feature applies.</span><span class="attributeValues">
                        One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the part in which the current feature should appear. Use '%all' when the feature should occur in every part.">part</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the part in which the current feature should appear. Use '%all' when the
                        feature should occur in every part.</span><span class="attributeValues">
                        One or more values of datatype <span style="font-weight: 500;">
                           a string matching the following regular expression: "(%all|#[\i][\c]+)"
                           </span>, separated by spaces.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the part staff on which a notated feature occurs. Use '%all' when the feature should occur on every staff.">partstaff</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Signifies the part staff on which a notated feature occurs. Use '%all' when the
                        feature should occur on every staff.</span><span class="attributeValues">
                        One or more values of datatype <span style="font-weight: 500;">
                           a string matching the following regular expression: "(%all|\d+(-\d+)?)"
                           </span>, separated by spaces.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the staff on which a notated event occurs or to which a control event applies. Mandatory when applicable.">staff</span><span class="attributeUsage">(recommended)</span><span class="attributeDesc desc">Signifies the staff on which a notated event occurs or to which a control event
                        applies. Mandatory when applicable.</span><span class="attributeValues">
                        One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                        as expressed in the written time signature.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                        as expressed in the written time signature.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.layerIdent">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerIdent</a></label><span class="classDesc">(MEI.shared) Attributes that identify the layer to which a feature applies.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Identifies the layer to which a feature applies.">layer</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Identifies the layer to which a feature applies.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.partIdent">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.partident.html">att.partIdent</a></label><span class="classDesc">(MEI.shared) Attributes for identifying the part in which the current feature appears.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the part in which the current feature should appear. Use '%all' when the feature should occur in every part.">part</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the part in which the current feature should appear. Use '%all' when the
                              feature should occur in every part.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "(%all|#[\i][\c]+)"
                                 </span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the part staff on which a notated feature occurs. Use '%all' when the feature should occur on every staff.">partstaff</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Signifies the part staff on which a notated feature occurs. Use '%all' when the
                              feature should occur on every staff.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "(%all|\d+(-\d+)?)"
                                 </span>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.staffIdent">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffIdent</a></label><span class="classDesc">(MEI.shared) Attributes for identifying the staff associated with the current feature.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the staff on which a notated event occurs or to which a control event applies. Mandatory when applicable.">staff</span><span class="attributeUsage">(recommended)</span><span class="attributeDesc desc">Signifies the staff on which a notated event occurs or to which a control event
                              applies. Mandatory when applicable.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.timestamp.logical">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.logical.html">att.timestamp.logical</a></label><span class="classDesc">(MEI.shared) Attributes that record a time stamp in terms of musical time, i.e., beats[.fractional
                           beat part].</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.timestamp.gestural">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.gestural.html">att.timestamp.gestural</a></label><span class="classDesc">(MEI.gestural) Attributes that record a performed (as opposed to notated) time stamp.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.gestural">
                     <div class="classHeading"><label class="classLabel">MEI.gestural</label><span class="classDesc">Gestural component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp.ges</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.gestural"><span class="ident attribute" title="Records the onset time in terms of ISO time.">tstamp.real</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the onset time in terms of ISO time.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Identifies the layer to which a feature applies.">layer</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Identifies the layer to which a feature applies.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the part in which the current feature should appear. Use '%all' when the feature should occur in every part.">part</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the part in which the current feature should appear. Use '%all' when the
                              feature should occur in every part.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "(%all|#[\i][\c]+)"
                                 </span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the part staff on which a notated feature occurs. Use '%all' when the feature should occur on every staff.">partstaff</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Signifies the part staff on which a notated feature occurs. Use '%all' when the
                              feature should occur on every staff.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">
                                 a string matching the following regular expression: "(%all|\d+(-\d+)?)"
                                 </span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Signifies the staff on which a notated event occurs or to which a control event applies. Mandatory when applicable.">staff</span><span class="attributeUsage">(recommended)</span><span class="attributeDesc desc">Signifies the staff on which a notated event occurs or to which a control event
                              applies. Mandatory when applicable.</span><span class="attributeValues">
                              One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part], as expressed in the written time signature.">tstamp</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                              as expressed in the written time signature.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(control change) – MIDI parameter/control change."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cc.html">cc</a></span>, <span class="ident element" title="(channel) – MIDI channel assignment."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chan.html">chan</a></span>, <span class="ident element" title="(channel pressure) – MIDI channel pressure/after touch."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chanpr.html">chanPr</a></span>, <span class="ident element" title="MIDI cue point."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cue.html">cue</a></span>, <span class="ident element" title="Arbitrary MIDI data in hexadecimal form."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/hex.html">hex</a></span>, <span class="ident element" title="MIDI marker meta-event."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/marker.html">marker</a></span>, <span class="ident element" title="MIDI text meta-event."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/metatext.html">metaText</a></span>, <span class="ident element" title="MIDI note-off event."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteoff.html">noteOff</a></span>, <span class="ident element" title="MIDI note-on event."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteon.html">noteOn</a></span>, <span class="ident element" title="MIDI port."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/port.html">port</a></span>, <span class="ident element" title="(program) – MIDI program change."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/prog.html">prog</a></span>, <span class="ident element" title="(sequence number) – MIDI sequence number."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/seqnum.html">seqNum</a></span>, <span class="ident element" title="(track name) – MIDI track/sequence name."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/trkname.html">trkName</a></span>, <span class="ident element" title="(velocity) – MIDI Note-on/off velocity."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/vel.html">vel</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.midi.event">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.midi.event.html">att.midi.event</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cc.html">cc</a><span class="elementDesc">(control change) – MIDI parameter/control change.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chan.html">chan</a><span class="elementDesc">(channel) – MIDI channel assignment.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chanpr.html">chanPr</a><span class="elementDesc">(channel pressure) – MIDI channel pressure/after touch.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cue.html">cue</a><span class="elementDesc">MIDI cue point.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/hex.html">hex</a><span class="elementDesc">Arbitrary MIDI data in hexadecimal form.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/marker.html">marker</a><span class="elementDesc">MIDI marker meta-event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/metatext.html">metaText</a><span class="elementDesc">MIDI text meta-event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteoff.html">noteOff</a><span class="elementDesc">MIDI note-off event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteon.html">noteOn</a><span class="elementDesc">MIDI note-on event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/port.html">port</a><span class="elementDesc">MIDI port.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/prog.html">prog</a><span class="elementDesc">(program) – MIDI program change.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/seqnum.html">seqNum</a><span class="elementDesc">(sequence number) – MIDI sequence number.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/trkname.html">trkName</a><span class="elementDesc">(track name) – MIDI track/sequence name.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/vel.html">vel</a><span class="elementDesc">(velocity) – MIDI Note-on/off velocity.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.midi">
                     <div class="classHeading"><label class="classLabel">MEI.midi</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cc.html">cc</a><span class="elementDesc">(control change) – MIDI parameter/control change.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chan.html">chan</a><span class="elementDesc">(channel) – MIDI channel assignment.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/chanpr.html">chanPr</a><span class="elementDesc">(channel pressure) – MIDI channel pressure/after touch.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/cue.html">cue</a><span class="elementDesc">MIDI cue point.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/hex.html">hex</a><span class="elementDesc">Arbitrary MIDI data in hexadecimal form.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/marker.html">marker</a><span class="elementDesc">MIDI marker meta-event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/metatext.html">metaText</a><span class="elementDesc">MIDI text meta-event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteoff.html">noteOff</a><span class="elementDesc">MIDI note-off event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/noteon.html">noteOn</a><span class="elementDesc">MIDI note-on event.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/port.html">port</a><span class="elementDesc">MIDI port.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/prog.html">prog</a><span class="elementDesc">(program) – MIDI program change.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/seqnum.html">seqNum</a><span class="elementDesc">(sequence number) – MIDI sequence number.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/trkname.html">trkName</a><span class="elementDesc">(track name) – MIDI track/sequence name.</span></div>
                        <div class="elementRef" data-module="MEI.midi"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/vel.html">vel</a><span class="elementDesc">(velocity) – MIDI Note-on/off velocity.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.midi.event"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.midi"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Attributes common to MIDI events.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerIdent</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.partident.html">att.partIdent</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffIdent</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.logical.html">att.timestamp.logical</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.gestural.html">att.timestamp.gestural</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>