---
title: "Work Package 5: Visualisation and Data Communication"
keywords: about
last_updated: October 5, 2017
tags: [wp5]
summary:
sidebar: artic_sidebar
permalink: wp5-vizualization.html
toc: false
folder: artic
---

### Interpretation and visualization of analyses to inform public health and epidemiology.

Practitioners in public health and epidemiology, instrumental in collecting pathogen samples for sequencing, are also those for whom analyses will provide direct and actionable information. 
Although experienced professionals, they may not be conversant in the technical aspects of sequence analysis so to translate real-time pathogen sequencing into tangible responses, we are developing approaches to visualizing and interpreting the information provided by rapid virus genome sequencing that are both compelling and detailed but also statistically sound.

### Development of a rich, interactive, web-based visualization and interpretation tool.

We will develop browser-based tools to visualize the analyses from WP4. The current evolutionary tree of the virus would always be available as a public website, that can be consulted by researchers and public health officials alike. Additionally, the website would give an overall view of transmission patterns and geographic spread from WP4.ii useful for public health officials engaging in outbreak response (Fig2). We will provide interactivity through a Javascript-based application and will incorporate modern information design principles. We have experience of developing such interactive applications including using these principles to visualize and interpret the continual evolution of human seasonal influenza (http://nextflu.org/) and for virus phylogenetic projected into geographical space.

With these tools in place, a sample from a new infection could be prepared and sequenced, and within 24 hours the public website would have fully incorporated this sequence into the analysis. The visualization would display hypotheses of epidemiological linkages, i.e. which cases represent direct transmission events, which represent secondary transmission, etc., generated by WP4.iv. Other personnel will be interested in larger scale questions regarding, for example, patterns of spatial spread and regional containment efforts (Fig5) and infections from a particular geographic location could be filtered and displayed. Further transmission insight would be gained by placing cases on a zoomable map and connecting cases with their inferred transmission network. Data on which genetic mutations separate nodes on the phylogeny would be available. Additionally, other epidemiological meta-data could be associated with leaves on the phylogeny to explore associations and patterns that aid comprehension of epidemic dynamics.

This system would aid epidemiological investigation by flagging cases for follow-up. With knowledge of genetic relatedness to known cases and transmission parameters like basic reproductive number R0 and generation time distribution, the system could provide an estimate and associated uncertainty for the number of undiscovered cases surrounding the focal case. Such estimates and visualization of geographic connections would be invaluable to contact tracing and containment efforts. If the focal case occurred in village A, but phylogenetic analysis suggests that ancestral infections resided in village B, then this informs the field epidemiologist where and when to look for a between-village travel connection. Additionally, the system would identify emerging phylogenetic clusters that appear to be growing rapidly. These would be flagged for epidemiological follow-up.

### Integration of virus genome analysis into a robust, automated, framework.

Finally, we will harden computational pipelines from WP4 to collate viral genomic data, align sequences, screen outliers and build phylogenies. 
This would run daily as an automated framework, pulling the latest sequences from our database and exporting phylogenies and metadata. 
The system may have strong computational demands, especially at the height of an outbreak with rapid expansion of genome data. 
We will design the system to be fully scalable for deployment in event of a public health emergency. 
This will be accomplished by packaging the analysis and visualization frameworks so they can be deployed at scale to distributed ‘cloud’ systems such as Amazon Web Services and the applicant’s CLIMB Cloud for phylogenetic computation and web hosting.

### [Presentations on workpackages are available here](presentations)

{% include links.html %}
