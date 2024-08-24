---
layout: default
nav_order: 1
parent: Guides
---

# Overview
{: .no_toc }
What is Dashboard, Item, Events & Actions?
{: .fs-6 .fw-300 }


<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

# Dashboard

The Dashboard is the central hub of Memseer, where you can view all your items and schedules in priority order.

![](../../assets/images/dashboard.png)

Each card on the Dashboard represents an item. Let's take a closer look at the information displayed on a single card:

![](../../assets/images/guides/overview/dashboard_card.png)

1. The name of the item and the year it was originated. By clicking item name, you will navigate to all the associated events / event log.
2. The last time an event was added, including the mileage (if applicable).
3. The item's settings.
4. The upcoming action that needs to be performed.
5. A "quick complete" button for the action.
6. An option to expand the card to see all scheduled actions sorted by upcoming priority.
7. An option to add an event to the item.

---

# Item

Item is something you want to keep an eye on and/or take care of. It can be a vehicle, device, personal health, special days, holiday and more. Each item contains [events](#events) - in order to keep a log and [actions](#actions) to be performed if so desired.

![](../../assets/images/guides/overview/new_item.png)

Item has several fields, which are optional.

**[work units](#work-units)** can be enabled if you need to keep track of thing with kilometers, miles or hours of operation, such as vehicles, airplanes or even treadmills - [see example](#work-units)

**origination date** - is a date when the item was manufactured/created or simply started working.

**active** - enables/disables calculation of schedule when [actions](#actions) are present.

**notifications** - enables/disables notifications (via email) of upcoming actions to be completed.

---

# Events

An event is a simple record of what took place. Every event has a name, date, notes and sometimes work units (we will talk about it later). You can create as many events as you want to record different type of event that took place.

![](../../assets/images/guides/overview/past_present_date.png)

**Note:** Date selection is limited to present or past dates, because this is an event, that took place already.

Event names are given in the present tense, for example: "replace air filter". There is no restriction on how you want to name an event; however we recommend sticking the present tense.

Event notes can contain anything you want to make note of. You can make a note of weather condition, part number, reasons for making certain decisions, the latest stock price and so on. I make extensive use of it when my kid gets sick. I record my observations in case I need to see a doctor at a later point, so I can provide as accurate information as possible.

![](../../assets/images/guides/overview/my_baby.png)

## Work units

Work units is an optional field for an event that appears whenever the item has work units enabled. Work units field comes with three options: kilometers, miles or hours. Here is an example:

![](../../assets/images/guides/overview/work_units.png)

Work units field comes handy when you are dealing with machinery that needs maintenance based on mileage rather than time passage. For example, a vehicle needs spark plugs replaced after certain amount of miles.

![](../../assets/images/guides/overview/example_sparkplugs.png)

---

# Actions

An action is a record that indicates conditions when something should be done. Each action has a name, condition and notes. Let's take a look at vehicle's actions:

![](../../assets/images/guides/overview/example_actions.png)

In the example we can see various actions that should be performed at certain conditions, based on time and/or kilometers. How does an action determines when the condition is met? The action looks into [events](#events), finds the same-named event, and calculates date when the action should take place.

![](../../assets/images/guides/overview/example_vehicle.png)

Effectively actions are like rules or specifications that should be applied to an [item](#item).  

## Action types:

There are several action types available to accommodate complex requirements. Let’s start with the basic types:

- Every 5 days
- Every 4 weeks
- Every 3 months
- Every 2 years
- Every 1000 miles

Check out this [vehicle example](../examples/vehicle.md). 

Next, we can add more conditions:

- Every 5 days between January and February
- Every 4 weeks between April and October
- Every 3 months between March and December

These actions with specific conditions apply during certain periods, allowing you to schedule seasonal tasks that need to be done only within those time frames. For example:

`Antiparasitic medication every 3 months between mar and nov`

![](../../assets/images/guides/overview/antiparasitic_medication_every_3_months_between_mar_and_nov.jpg)

This example illustrates [cat care](../examples/my_cat.md), where the cat needs to take medication every 3 months during the outdoor season.

Now, let’s look at more specific conditions:

- Every 4 weeks on Monday
- Every 3 months on 2nd
- Every 2 years on February 3rd

These actions allow for a tight schedule and precise tracking. For example, the water bill might arrive every 3 months:

`Water bill every 3 months on 15th`

![](../../assets/images/guides/overview/water_bill_every_3_months_on_15th.jpg)

Or property taxes might be due every year on February 20th:

`Property tax every 1 year on feb 20th`

![](../../assets/images/guides/overview/property_tax_every_1_year_on_feb_20th.jpg)


## Creating action(s)

There are two ways to create actions: directly, by navigating to "Item & Actions" and adding new actions, or by creating actions from existing events. 

The first method involves navigating to "Item & Actions" and adding new actions. Here's an image that illustrates this process:

![](../../assets/images/guides/overview/create_action_edit_item_and_actions.png)

The second method is useful when you already have events and want to create actions based on them. To do this, navigate to an event log and identify the event that requires an action. For example, let's say we have an event called "check water chemistry," which occurs every week based on the dates between events.

![](../../assets/images/guides/overview/example_hot_tub_check_water.png)

To create an action from this event, click on the "+" plus sign. You will be redirected to the "Item & Actions" page, where the newly created action will be highlighted:

![](../../assets/images/guides/overview/newly_created_action.png)

Next, you need to set the unit to "1" and select "weeks." Leave everything else as default and click "Done":

![](../../assets/images/guides/overview/newly_created_action_complete.png)

Congratulations! You have successfully created an action. You can view it on the dashboard and also find it under the 'i' icon in the top-right corner of the event name:

![](../../assets/images/guides/overview/example_hot_tub_check_water_complete.png)
