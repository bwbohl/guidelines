---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.keySigDefault.log"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.keySigDefault.log">att.keySigDefault.log</h3>
      <div class="specs">
         <div class="desc">Used by staffDef and scoreDef to provide default values for attributes in the logical
            domain that are related to key signatures.
            <div class="chapterLinksBox"><a class="chapterLink desc" href="/guidelines/v4/content/cmn.html#cmnDefs">4.2.2 Defining Score Parameters for CMN</a></div>
         </div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.shared</div>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Written key signature.">key.sig</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Written key signature.">key.sig</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Written key signature.</span><span class="attributeValues">
                        One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keyfifths.html">data.KEYFIFTHS</a>, separated by spaces.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Written key signature.">key.sig</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Written key signature.</span><span class="attributeValues">
                              One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keyfifths.html">data.KEYFIFTHS</a>, separated by spaces.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Written key signature.">key.sig</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Written key signature.</span><span class="attributeValues">
                              One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keyfifths.html">data.KEYFIFTHS</a>, separated by spaces.
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(score definition) – Container for score meta-information."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a></span>, <span class="ident element" title="(staff definition) – Container for staff meta-information."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.keySigDefault.log">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.scoreDef.log">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.log.html">att.scoreDef.log</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.staffDef.log">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffdef.log.html">att.staffDef.log</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a><span class="elementDesc">(staff definition) – Container for staff meta-information.</span></div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a><span class="elementDesc">(staff definition) – Container for staff meta-information.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet remarks">
            <div class="label">Remarks</div>
            <div class="statement remarks">
               <p>Mixed key signatures, e.g. those consisting of a mixture of flats and sharps (Read,
                  p. 143,
                  ex. 9-39), and key signatures with unorthodox placement of the accidentals (Read,
                  p. 141)
                  can be encoded using the <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/keysig.html">keySig</a> element.
               </p>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.keySigDefault.log"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.shared"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Used by staffDef and scoreDef to provide default values for attributes in the logical
                           domain that are related to key signatures.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"key.sig"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Written key signature.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype <span class="attribute">maxOccurs=</span><span class="attributevalue">"unbounded"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:ref
                                       
                                       <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keyfifths.html">data.KEYFIFTHS</a>"</span></span>
                                       /&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/attList&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;remarks&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;p&gt;</span>Mixed key signatures, e.g. those consisting of a mixture of flats and sharps (Read,
                              p. 143,
                              ex. 9-39), and key signatures with unorthodox placement of the accidentals (Read,
                              p. 141)
                              can be encoded using the 
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;gi <span class="attribute">scheme=</span><span class="attributevalue">"MEI"</span>&gt;</span>keySig<span data-indentation="4" class="element">&lt;/gi&gt;</span></div> element.<span data-indentation="3" class="element">&lt;/p&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/remarks&gt;</span></div>
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