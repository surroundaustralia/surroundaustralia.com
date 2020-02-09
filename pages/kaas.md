---
layout: page
title: "KaaS"
permalink: /kaas
---
# Knowledge as a Service (KaaS)

SURROUND offers a very powerful *as a Service* capability: [Knowledge as a Service (KaaS)](https://en.wikipedia.org/wiki/Knowledge_as_a_service). 

Our KaaS - see [Illumin](/illumin) - accesses our [Knowledge Graphs](https://en.wikipedia.org/wiki/Graph_(abstract_data_type)) which you can use to enhance your own data and processes through the addition of *context*.

## What is a KaaS?

A KaaS give you *knowledge*, as opposed to just *data* or *information*, which you can use directly or with your own information. It presents data definitions, terminology, data associations and learned experience which provide more than just the facts of data or information: you understand what the information's about, what it can tell you and how well you can trust it. 

<style>
.tooltip {
  position: relative;
  display: inline;
  border-bottom: 1px dotted black;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}
</style>
<div style="display:grid; grid-template-columns: 1fr 1fr;">
    <div style="text-align:center;">
        <a href="images/KaaS.svg"><img src="images/KaaS.svg" style="width:400px" /></a><br />
        <span style="font-size:small;">An overview of SURROUND's <a href="/illumin">Illumin</a> KaaS and its underlying resources.</span>
    </div>
    <div>
        <p>SURROUND's KaaS is available via an <span class="tooltip">API<span class="tooltiptext">Application Programming Interface - a system to answer queries</span></span> which accesses information from our various knowledge graphs. This includes both domain information as well as reference information, such as overarching data models and taxonomies of terms.</p>
        <p>See our <a href="/illumin">Illumin</a> product to learn about the specific information our KaaS utilises.</p>
        <h4>Elements of a KaaS</h4>
        <p>The main parts of a KaaS are:</p>
        <ul style="line-height: 2em;">
            <li>
                <strong style="font-size: large;">Domain Data Sources</strong>
                <ul>
                    <li>Knowledge Graphs or other collections of information</li>
                    <li>Potentially multiple sources are included to allow <em>context</em> in the form of different, mapped, datasets </li>
                </ul>
            </li>
            <li>
                <strong style="font-size: large;">Reference Data Sources</strong>
                <ul>
                    <li>Upper Ontologies - high-level models for integrating data</li>
                    <li>Taxonomies of terms - provide data definitions</li>
                </ul>
            </li> 
            <li>
                <strong style="font-size: large;">Context Streams</strong>
                <ul>
                    <li>Outdated information isn't knowledge</li>
                    <li>We can pull in information from continuously changing sources and add them to the data used by the KaaS</li>
                </ul>                
            </li>           
        </ul>
    </div>
</div>

## How can you use it?

<style>
    #ucs {
        display:grid; 
        grid-template-columns: 1fr 1fr 1fr;
    }
    #ucs div {
        text-align: center;
    }
</style>
<div id="ucs">
    <div style="grid-column:1;">
        <h4>Interoperability</h4>
        <p>Most organisations have multiple siloes of data that are not easily made interoperable. Data from Silo X may be combined with data from Silo Y by first associating each with deep context via a KaaS which includes models, teminology and so on. Then, with each silo's data now containing context, they may be able to be crosswalked via associations between each help within a KaaS's context pool.</p>
    </div>
    <div style="grid-column:2;">
        <h4>Data Insights</h4>
        <p>Data often contain more information than it is easy to glean from simple used - patterns and correlations that elude initial inspection even within a single silo. KaaSs can be used to enhance data definitions, data presentation and data categorisation so that patterns are more easily identifiable.</p>
    </div>
    <div style="grid-column:3;">
        <h4>Situational Awareness</h4>
        <p>Information is always used within an environment and a KaaS can provide access to multiple domain knowledge graphs that contain both domain-specific knowledge and also continuously updated datasets of current domain information. These can be used to supply a user with enhanced environment situational awarness as domain knolwedge and trends become known through the KaaS.</p>
    </div>    
</div>