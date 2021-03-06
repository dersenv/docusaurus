---
id: observation
title: Observation Data Model
sidebar_label: Observation (ODM)
description: Schema for Observations in PPSR

---

An observation is a collection of information recorded based on something that has been seen, heard, or noticed. In the context of PPSR Core; observations represent the information collected by the public.

The **O**bservation **D**ata **M**odel describes the structure of observational records collected as part of Public Participation in Scientific Research. It is the basic unit of research information and includes:
- Location
- Time
- Additional attributes specific to the dataset

This is still a work in progress and the Data & Metadata working group is sorting through existing platforms and projects to find commonalities. Please [contact us](contribute) to get involved.

It is intended to comprise a series of domain appropriate sets of attributes and/or schemas which are required for effective and useful aggregation of data for scientific use. An example of this would be the Darwin Core standard used for global biodiversity occurrence data. Other domains also have their specific standards. The ODM will recommend application of relevant existing domain standards where they exist, develop new models where they don't, and will seek to identify and standardize common attributes across domains to enable multi-disciplinary aggregation of datasets on those attributes for cross-disciplinary analysis.

<table className="table table-bordered table-hover table-condensed">
<thead><tr><th title="Field #1">Suffix abbreviation</th>
<th title="Field #2">Name of standard</th>
<th title="Field #3">URL</th>
</tr></thead>
<tbody><tr>
<td>dct / dcterms / dcmitype</td>
<td>Dublin Core Ontology</td>
<td>
<a href="https://purl.org/dc/terms/">purl.org/dc/terms/</a> 
<br/>
<a href="https://purl.org/dc/dcmitype/">purl.org/dc/dcmitype/</a>
 </td>
</tr>
<tr>
<td>dwc / dwcterms</td>
<td>Darwin Core Terms</td>
<td>
<a href="http://rs.tdwg.org/dwc/terms/">rs.tdwg.org/dwc/terms/</a>
</td>
</tr>
<tr>
<td>cosi</td>
<td>Core Ontology of Scientific Investigation</td>
<td>
<a href="https://purl.org/net/cosi#">purl.org/net/cosi#</a>
</td>
</tr>
<tr>
<td>dcat</td>
<td>Data Catalog Vocabulary</td>
<td>
<a href="https://www.w3.org/TR/vocab-dcat/">www.w3.org/TR/vocab-dcat/</a>
</td>
</tr>
<tr>
<td>prov</td>
<td>PROV-DC</td>
<td>
<a href="https://www.w3.org/ns/prov#">www.w3.org/ns/prov#</a>
</td>
</tr>
<tr>
<td>foaf</td>
<td>Friend of a Friend Ontology</td>
<td>
<a href="http://xmlns.com/foaf/0.1/">xmlns.com/foaf/0.1/</a>
</td>
</tr>
<tr>
<td>ISO</td>
<td>ISO 19115</td>
<td>
<a href="https://www.iso.org/obp/ui/#iso:std:iso:19115:ed-1:v1:en">www.iso.org/obp/ui/#iso:std:iso:19115:ed-1:v1:en</a>
</td>
</tr>
</tbody></table>