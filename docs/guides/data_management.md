---
layout: default
title: Data management
parent: Guides
nav_order: 3
---

# Data management
{: .no_toc }

How to import & export data
{: .fs-6 .fw-300 }
---

Your data split into 2 parts: [Item](../guides/overview.md#item) (includes actions) and [Events](../guides/overview.md#events). Both parts are independent of each other and can be imported/exported separately. 

---

- TOC
{:toc}

--- 

## Item

### Export

In order to export your item, go to dashboard, find desired item and click edit item (gear image).

![](../../assets/images/guides/import_export/item_settings_gear.png)

Next scroll all the way to the bottom of the page and find "Export Data" button on the right side.

![](../../assets/images/guides/import_export/item_settings_export.png)

Click "Export Data" and item file will be saved to your device under item's name, for example:\
`Miata GT.json`


### Import

In order to import a new item, go to dashboard, scroll to the bottom and click on "Add new item".

![](../../assets/images/guides/import_export/add_new_item.png)

Next, click on "Import".

![](../../assets/images/guides/import_export/new_item_import.png)

Select an import file (example: `Miata GT.json`) and in a second you will see populated item

![](../../assets/images/guides/import_export/newly_imported_item.png)

---

## Events

### Export

When exporting, you have two options: export events only, or export events with file attachments. Let's first discuss how to export events:

#### Export Events
To export events, navigate to the dashboard and locate the desired item. Click on the item name.

![](../../assets/images/guides/import_export/item_events.png)

Next, scroll to the bottom of the page and find the "Export Data" button on the right side.

![](../../assets/images/guides/import_export/events_export.png)

Click "Export Data". The events file will be saved to your device under the item's name, for example:
`Miata GT.csv`

#### Exporting Events with Attachments

To export events with attachments, go to the dashboard, find the desired item, and click on the item name.

![](../../assets/images/guides/import_export/item_events.png)

Then, scroll to the bottom of the page and locate the "Export Data & Attachments" button on the right side.

![](../../assets/images/guides/import_export/events_export.png)

Click "Export Data & Attachments". A zip file will be saved to your device under the item's name, for example:
`Miata GT.zip`. This archive will contain `Miata GT.csv` along with all attached files. 

### Import

In order to import events, go to dashboard and click on the item's name.

![](../../assets/images/guides/import_export/import_events.png)

Note: the item does NOT have "Last event:" and has a bunch of "Late" actions. This is normal since there are no events.

Click on item's name.

![](../../assets/images/guides/import_export/import_events_item_name.png)

On the bottom right click "Import", select file (example: `Miata GT.csv`) and in a second you will see populated events.

![](../../assets/images/guides/import_export/import_events_import_button.png)
