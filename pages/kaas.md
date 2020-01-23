---
layout: page
title: "KaaS"
permalink: /kaas
---
# Knowledge as a Service (KaaS)

SURROUND offers a very powerful [Knowledge as a Service (KaaS)](https://en.wikipedia.org/wiki/Knowledge_as_a_service) that accesses our [Knowledge Graphs](https://en.wikipedia.org/wiki/Graph_(abstract_data_type)) which you can use to enhance your data and processes.

## What is our KaaS?

<div style="display:grid; grid-template-columns: 1fr 1fr;">
    <div style="text-align:center;">
        <a href="images/KaaS.svg"><img src="images/KaaS.svg" style="width:400px" /></a><br />
        <span style="font-size:small;">An overview of SURROUND's KaaS and its underlying resources.</span>
    </div>
    <div>
        <p>SURROUND's KaaS accesses data in one of our domain knowledge graphs such as Finance (FinKG), Government (GovKG) or the resources sector (ResKG), just as a <a href="https://en.wikipedia.org/wiki/Data_as_a_service">Data as a Service</a> does. It also accesses a <em>Reference Data Source</em> which consists of general data models, background datasets and perhaps streaming information to provide <em>context</em> to the information delivered, turning it into <em><strong>knowledge</strong></em>.</p>
        <h4>Elements of our KaaS</h4>
        <p>The main parts of our KaaS are:</p>
        <ul>
            <li>
                <strong>Domain Data Source</strong>
                <ul>
                    <li>One of our Knowledge Graphs</li>
                    <li><a href="/govkg">GovKG</a></li>
                    <li>FinKG</li>
                </ul>
            </li>
            <li>
                <strong>Reference Data Source</strong>
                <ul>
                    <li>SURROUND's surrpoting Knolwedge Graph for all applications</li>
                    <li>Upper Ontologies - a collection of widely used data models to provide data definitions</li>
                    <li><a href="/govkg">GovKG</a> - for specialised domains, government knowledge in GovKG is reference data</li>
                    <li>Context Stream - for different domains we provide a streaming data analysis service which analyses information relevant to that domain: current context</li>
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
        <p>Most organisations have multiple siloes of data that are not easily made interoperable. Data from Silo X may be combined with data from Silo Y by first associating each with deep context via the KaaS. Then, with each silo's data now containing context, they may be able to be crosswalked via associations between each help within the KaaS context pool.</p>
    </div>
    <div style="grid-column:2;">
        <h4>Data Insights</h4>
        <p>Data often contain more information than it is easy to glean from simple used - patterns and correlations that elude initial inspection. Our KaaS can be used to enhance data definitions, data presentation and data categorisation so that patterns are more easily identifiable.</p>
    </div>
    <div style="grid-column:3;">
        <h4>Situational Awareness</h4>
        <p>Information is always used within an environment and SURROUND provides several domain knowledge graphs that contain both domain-specific knowledge and also continuously updated datasets of current domain information. These can be used to supply a user with enhanced environment situational awarness as domain knolwedge and trends become known through the KaaS.</p>
    </div>    
</div>