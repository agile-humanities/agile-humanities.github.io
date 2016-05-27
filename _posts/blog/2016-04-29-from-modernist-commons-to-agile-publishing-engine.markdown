---
layout: post
title: "From Modernist Commons to Agile Publishing Engine"
date: 2016-04-29 16:54:46
author: Dean Irvine
categories: 
- blog
- digital humanities
- open source
- publishing 
- SaaS
- Islandora
- Cloud
img: post01.jpg
thumb: thumb01.jpg
---
[Modernist Commons][modernist] is an Islandora-based digital repository, editorial workbench, and critical-edition publication platform designed by [Editing Modernism in Canada][emic] (EMiC). It integrates a wide range of open-source systems and tools (Islandora, Tesseract OCR, CWRC Writer, Shared Canvas, Internet Archive Viewer, Open Seadragon Viewer, Calliope, and CollateX). With these tools, users can ingest images and generate transcriptions, as well as edit and mark up both transcriptions and images using a single graphical interface, which supports overlapping TEI-XML and RDF markup. Users can also perform algorithmically generated collations of transcriptions, which can be visualized in different ways using Calliope and CollateX. The Modernist Commons provides a critical-edition interface so that editors can assemble images, audio and video, critical apparatus, and variant visualizations in a configurable reading environment. <!--more-->Our most recent development has been the migration articles from Yale University’s Modernism Lab to the repository and the integration of an editing interface for creating new articles that allows users to cross-reference other articles in the repository using SOLR-based look-up.

Modernist Commons was initially developed with resources from the Social Sciences and Humanities Research Council of Canada. It was built in collaboration with a consortium of grant-funded research participants and partners. Grants that funded early phases of development are all but finished, so the infrastructure is now maintained through a different economic model and partnership. That new model and partnership includes the support of developers affiliated with the Agile network.

### Agile Publishing Engine
EMiC has already demonstrated the capability of publishing critical editions through the Modernist Commons. Our next phase of development will see the production of the Agile Publishing Engine (APE).

First, we plan to extend the Modernist Commons’ multimodal functionality to accommodate not just critical editions but multiple scholarly genres (monographs, essay collections, anthologies, etc.) and integrate a production workflow designed for scholarly publishing. This will require an investment of additional resources in the development of our open-source web-based repository, editorial workbench, and publication platform.

Second, we will integrate the Drupal-based [ONIXlive][onix] storefront and deployment engine, which has already been developed by the [Intelligent Machines][intelligent] collective. Agile’s ongoing collaboration with the IM collective will target a broad client base in the publishing sector. With the combination of the extended functionality of an Islandora-based repository, editorial workbench, and publication platform and the ONIXLive engine and storefront, we will be in a position to deliver a complete production, management, and distribution system for born-digital scholarly publishing.

### By Design, Cloud, and Open
APE will be available in three configurations:

1. **APE by Design**, a customized package. Agile provides you with a hosted instance of APE scaled to your requirements and deployed on either your own or third-party hosted infrastructure.

2. **APE Cloud**, a subscription-based SaaS (Software as a Service) system. There are limitations to how much customization can be performed, but this is a turnkey solution.

3. **Open APE**, an open-source option. If your organization has its own IT resources with supporting infrastructure and skills you can obtain APE from GitHub and configure your own instance.

[modernist]: http://modernistcommons.ca

[emic]: http://editingmodernism.ca 

[onix]: http://www.intelligentmachines.ca/publishers

[intelligent]: http://www.intelligentmachines.ca