<div class="nested0" aria-labelledby="ariaid-title1" topicindex="1" topicid="edr1508194035653" id="edr1508194035653"><h1 class="title topictitle1" id="ariaid-title1">GMMProfile (ML Engine)</h1><div class="body conbody">
<p class="p">The GMMProfile function takes the output of the function <a href="zgv1558460260471.md#mwd1507666023473">GMM (ML Engine)</a> and outputs information about how each cluster diverges from the global data statistics.</p></div><div class="topic reference nested1" aria-labelledby="ariaid-title2" topicindex="2" topicid="yde1507734769997" xml:lang="en-us" lang="en-us" id="yde1507734769997">
<h2 class="title topictitle2" id="ariaid-title2">GMMProfile Syntax</h2><div class="body refbody"><div class="section" id="yde1507734769997__section_N1000E_N1000C_N10001">
<h3 class="title sectiontitle">Version <span>1.4</span></h3><pre class="pre codeblock" xml:space="preserve"><code>SELECT * FROM GMMProfile (
  <span>ON { <var class="keyword varname">table</var> | <var class="keyword varname">view</var> | (<var class="keyword varname">query</var>) }</span> PARTITION BY 1
) AS <var class="keyword varname">alias</var>;</code></pre></div></div></div></div>
