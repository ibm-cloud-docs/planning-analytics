---

copyright:
   years: 2023
lastupdated: "2023-01-31"

keywords: tutorial
subcollection: cognos-analytics

content-type: tutorial
services: 
account-plan: lite 
completion-time: 25m 

---

{:shortdesc: .shortdesc}
{:screen: .screen}  
{:codeblock: .codeblock}  
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:external: target="_blank" .external}
{:step: .step}


# Create a story, exploration, data module, and report
{: #tutorial-cognosanalytics}
{: toc-content-type="tutorial"} 
{: toc-services=""} 
{: toc-completion-time="15m"} 

In the following tutorials, use {{site.data.keyword.cognosanalytics_full}} (Experimental) to create a story, exploration, data module, and a report.
{: shortdesc}

For more tutorials, videos, and hands-on labs, see [IBM Demos: Cognos Analytics](https://www.ibm.com/demos/collection/IBM-Cognos-Analytics/).



## Creating a story
{: #create_story}
{: step}
Stories are an effective way to present and share your data. In this tutorial, you learn how to create a story, an outline, and how to animate a scene.

1. On the home page, click the `Open menu` icon ![Open menu](images/icon_open_menu.jpg "Open menu icon") and then click `New`.
2. Click `Story`.
3. Select a `Slideshow` transition style, and then click `Create`.
   - A slideshow tells a story through a series of slides or scenes. 
   - A guided journey starts with the full picture of the story and then pans and zooms into the details across the canvas. 
4. Ensure that you are in edit mode. 
5. Create an outline for your story. Add scenes, such as an introduction, past performance, and a conclusion.
6. Click `Scene selector` and then click a scene to edit.
7. Select widgets or visualizations to add to your canvas. Continue this process until your scenes are populated.
8. Click `Open timeline` and adjust the widgets along the timeline. 
9. Use`Open animation properties` on widgets to add animation, such as transitions.
10. Click `Play` to view the story presentation.
11. Click `Save` to save your story.

To create a story from an existing dashboard, open the dashboard and click `Save as a story`. By default, all scenes are 5 seconds long.
{: tip}

For more information, see [Stories](https://www.ibm.com/support/knowledgecenter/en/SSEP7J_11.1.0/com.ibm.swg.ba.cognos.ug_ca_dshb.doc/ca_stories_intro.html).


## Creating an exploration
{: #create_exploration}
{: step}
Explore is a flexible workspace where you can discover and analyze data. You can also explore an existing visualization from a dashboard or story. Uncover hidden relationships and identify patterns that turn your data into insights. 

Follow these steps to create an exploration from the `New` menu:
1. On the home page, click the `Open menu` icon ![Open menu](images/icon_open_menu.jpg "Open menu icon") and then click `New`. 
2. Click `Exploration`.
3. Select a data source and click `Add`. A starting points page is displayed with suggestions for how to get started. 

Follow these steps to create an exploration from a data asset:
1. Go to your data asset and select it.
2. Click the `Action menu` icon.
3. Select `Create exploration`.

Follow these steps to create an exploration from an existing dashboard or story:
1. Open your dashboard or story.
2. Select a visualization.
3. Click the `Explore` icon ![Exploration](images/icon_explore.jpg "Exploration icon") in the toolbar. Select `New exploration` or `Add to existing...`.

For more information, see [Explorations](https://www.ibm.com/support/knowledgecenter/en/SSEP7J_11.1.0/com.ibm.swg.ba.cognos.ca_explorations.doc/ca_explorations_intro.html).


### Exploring your data
{: #explore_data}
When you create an exploration, you can start from a data source. A starting points page is displayed with suggestions for how to get started.

You can type a column name that appears in your data source. Or, you can click one of the suggested columns that the system identifies as interesting. If you're not sure which column to start with, click `Skip - show me anything` to see a relationship diagram with some suggested starting point visualizations. 

In the relationship diagram, the column that you start with is the prime focus and is represented by a dark blue node. Related fields are represented by purple nodes. Lines connect the nodes and represent relationships. The thickness of the line indicates the strength of the relationship. 

The strongest primary relationships are displayed by default and are the direct relationships between the prime focus and the related fields. Secondary relationships are the relationships between other fields directly or indirectly related to the target.


## Creating a data module
{: #create_data_module}
{: step}
{{site.data.keyword.cognosanalytics_short}} provides web-based, self-service data modeling capabilities. You can use data modeling to fuse together many sources of data, including relational databases, Hadoop-based technologies, spreadsheets, text files, and more. Using these sources, a data module is created that can then be used in reports, dashboards, or explorations.

1. On the home page, click the `Open menu` icon ![Open menu](images/icon_open_menu.jpg "Open menu icon") and then click `New`.
2. Click `Data module`.
3. In the `Select sources` dialog box, select one or more sources from:
- Saved data in the `Team content` or `My content` folder;
- `Data servers and schemas`; or
- Upload a local file.
4. If all selected sources contain one table each, the basic data module is created. If the sources contain multiple tables, you must select the tables manually or discover related tables.
5. In the `Data module` pane, use the data grid view to expand the data sources and view their tables, columns, and members.
6. Click `Relationships` to view how tables are related.
7. The data module is validated automatically. Broken references are identified by a failed validation icon in the data module tree and diagram.
8. To create a test report from your data module, click `Try it` in the application toolbar. 
9. To save the data module, click `Save` or `Save as`. 

For more information, see [Data Modules](https://www.ibm.com/support/knowledgecenter/en/SSEP7J_11.1.0/com.ibm.swg.ba.cognos.ca_mdlg.doc/c_ca_data_modeling.html).


## Creating a report
{: #create_report}
{: step}
Learn how to create professional reports (such as invoices and statements) and share the results across your organization.

1. On the home page, click the `Open menu` icon ![Open menu](images/icon_open_menu.jpg "Open menu icon") and then click `New`.
2. Click `Report`.
3. Select the default template and theme. Click `Create`.
4. Select a data source from your content folders. For example, you can select a data module or a package.
5. Drag single or multiple data objects from the objects pane to your report canvas.
6. Click the `Properties` icon ![Properties](images/icon_properties.jpg "Properties icon") in the toolbar to customize colors, fonts, and more.
7. From the `More` menu ![More](images/icon_more.jpg "More icon"), validate the contents of your report and resolve any errors.
8. Click `Run` and selection a run option to determine the output format. For example, you can generate an HTML report.
9. Click the `Share` icon ![Share](images/icon_carbon_share.jpg =20x20 "Share icon") to send the report to a colleague by email.
10. Click the `Save` icon to save the report to your folder.

For more information, see [Reporting](https://www.ibm.com/support/knowledgecenter/en/SSEP7J_11.1.0/com.ibm.swg.ba.cognos.ug_cr_rptstd.doc/c_understand_rs.html).
        
