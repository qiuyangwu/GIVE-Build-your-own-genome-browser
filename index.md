---
title: GIVE: Build your own genome browser
author: Qiuyang
header-includes:
  - \usepackage{multicol}
---
# GIVE: Build your own genome browser

GIVE  is an open source programming library that allows anyone with HTML programming experience to build custom genome browser websites or apps.  With a few lines of codes, one can add to a personal webpage an interactive genome browser that host custom data. It typically takes less than half a day to build a genome browser website with GIVE. 
This portable library encapsulates novel data communication and data visualization technologies, including new data structures and new memory management methods that enable efficient data transfer between the data-hosting website and internet browsers.  
GIVE is the acronym of **G**enomic **I**nteraction **V**isualization **E**ngine, although GIVE's utilities have outgrown its original name.

| [GIVE Tutorial](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/tree/master/tutorials)  | [GIVE Manual](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/blob/master/manuals/index.md) |
|--------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| Example websites and line by line explanation.                                                                     | A full technical reference.                                                                                                |  

## [A 2-minute example](https://jsfiddle.net/frankyan/mcdng033/1/)

<img align="left" width="50%" height="50%" border="2%" src="figures/2-minute_example.png">
Just copy paste the two following lines to jsfiddle, an online HTML testing website for testing of your own HTML codes. 1) Go to  jsfiddle, 2) copy paste the following lines to the HTML panel (top left), 3) hit "run" button.
Congratulations! You are seeing your first genome browser webpage. You can modify and change using HTML as your wish.
```
<script src="https://www.givengine.org/libWC/webcomponents-lite.min.js"></script> 
<link rel="import" href="https://www.givengine.org/lib/chart-controller/chart-controller.html">
<!-- Embed the browser in your web page -->
<chart-controller title-text="long-range promoter contacts with capture Hi-C" ref="hg19" num-of-subs="2" coordinates='["chr18:19140000-19450000", "chr18:19140000-19450000"]' group-id-list='["genes", "CHi-C_promoter", "customTracks"]'>
</chart-controller>
```

****************

## Examples of custom genome browsers built with GIVE
-------------------------------------------------------------------------------------------------------------------------------
 Single-cell transcriptome website  <img align="right" width="50%" height="50%" border="2%" src="figures/give_singlecell.png"> 
                                                                                                                                    
-------------------------------------------------------------------------------------------------------------------------------

----------------

----------------

Single-cell transcriptome website
<img align="right" width="50%" height="50%" border="2%" src="figures/give_singlecell.png">

-------------------------------------------------------------------------------------------------------------------------------
<!--
A website for displaying genome interaction (Hi-C) data together with other data types.
<img align="right" width="50%" height="50%" border="2%" src="figures/give_hic.png">

----------------

A web browser for human ENCODE datasets
<img align="right" width="50%" height="50%" border="2%" src="figures/give_encode.png">

----------------

A website for genome-wide RNA-DNA interactions
<img align="right" width="50%" height="50%" border="2%" src="figures/give_RNAinteraction.jpg">

----------------

A website for displaying genome interaction (Capture Hi-C) data
<img align="right" width="50%" height="50%" border="2%" src="figures/give_hic1.png">

----------------

A website for displaying genome interaction (ChIA-PET) data
<img align="right" width="50%" height="50%" border="2%" src="figures/give_chiapet.png">

----------------

Citation: Xiaoyi Cao, Zhangming Yan, Qiuyang Wu, Alvin Zheng, Sheng Zhong, Building a genome browser with GIVE,  bioRxiv, 2017, [https://doi.org/10.1101/177832](https://doi.org/10.1101/177832).

----------------

© COPYRIGHT 2017 GIVE Authors. Code Licensed under the Apache License 2.0. Documentation licensed under CC BY 3.0. 
-->
