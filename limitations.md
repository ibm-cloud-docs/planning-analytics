---
copyright:
  years: 2023
lastupdated: "2023-02-08"

keywords:
subcollection: planning-analytics

content-type: learn

---

{:codeblock: .codeblock}
{:note: .note}
{:pre: .pre}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:table: .aria-labeledby="caption"}
{:tip: .tip}
{:video: .video}
{:external: target="_blank" .external}
{:step: data-tutorial-type='step'}

# Product Limitations
{: #product_limitations}

The following is a list of features that are currently not supported in {{site.data.keyword.PA_SaaS_full}}.

## Flat file load and Export
{: #flat-file-load-export}

Flat file load and Export will be limited to files smaller than 1GB, in CSV or .txt and brought in via drag-and-drop using the File Manager. You can create Flat files through a TI process, but you can’t retrieve the files from File Manager.

## Database file size limitation
{: #db-file-size}

There is a 5GB file size limitation when backing up or restoring a database in {{site.data.keyword.PA_SaaS_full}}. An automatic database backup fails if the resulting archive file is greater than 5GB. Similarly, a database restore fails if the source archive is greater than 5GB. Due to this limitation, it is suggested that you use the manual backup feature.

## The following websheet features are not supported in Planning Analytics as a Service:
{: #websheet-features}

- Sandboxes
- Undo/Redo
- Annotations
- Cell indicators (holds, annotations)
- Picklists
- Websheets will only open when drag and dropped.
