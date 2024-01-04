---
name: Inventory Management System [Cloud Computing Project]
tools:
  [Node-RED, NeCTAR, IBM Cloud Services, Microsoft Teams, Teamwork, Uni Project]
image: /assets/images/cloudComputing/cloudComputing_overview.PNG
description: Use Node-RED and other cloud services and tools to develop a cloud-hosted application to assist with Inventory Management.

external_url:
---

# Cloud Computing project

---

[Preview](https://replit.com/@TienBui19/DivingCalculations)

{% capture list_items %}
Screenshots
Demo video
Overview
Technical details
My contribution
Source code
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

# Screenshots

{% capture carousel_images %}
/assets/images/cloudComputing/cloudComputing_1.png
/assets/images/cloudComputing/cloudComputing_2.png
/assets/images/cloudComputing/cloudComputing_3.png
/assets/images/cloudComputing/cloudComputing_4.png
/assets/images/cloudComputing/cloudComputing_5.png
/assets/images/cloudComputing/cloudComputing_6.png
/assets/images/cloudComputing/cloudComputing_7.png
{% endcapture %}
{% include elements/carousel.html %}

# Demo video

{% include elements/video.html id="I9iy-jVv-5Q" %}

# Overview

## Purpose

This project aims to use `Node-RED` and other tools to develop a **cloud-hosted application** to assist with Inventory Management.

## Functionality

- **Manage stocks** in the inventory of individual stores as well as the total number of stores
- **Check for low-stock** and nearly expired products at each store and notify store managers to make new orders
- Generate **visual summaries** of inventory products using charts and graphs for store managers and business owners
- Display **product availability** on the grocery store website using stock data to help customers check what products are available before coming to the store
- Incorporate a **chatbot** to assist customers with inquiries while visiting the store's website.

## Target audience

Small grocery stores with one or more stores that only sell in-store.

# Technical details

## Technologies and Tools used

| **Tech/Tool**            | **Usage**                         |
| ------------------------ | --------------------------------- |
| IBM Cloud Foundry        | Deploy Node-RED app, IBM Cloudant |
| IBM Cloud Object Storage | Image storage                     |
| IBM Cloudant Database    | Store Node-RED app data           |
| IBM Watson Assistant     | Develope Chatbot content          |
| IBM Continuous Delivery  | Auto deploy Node-RED app          |
| Node-RED                 | Main Development environment      |
| Nectar Cloud instance    | Deploy Client site                |
| VS Code                  | IDE                               |
| Microsoft Teams          | Communication and collaboration   |

## Application components

- A **Node-RED page** for modifying functions of the application:
  - Interacting with the database.
  - Providing APIs for the Admin page and the Client page.
  - Sending customized notifications on stock status to store managers.
- An **Admin page** for store managers and business owners to manage their inventory, including the following functions:
  - Summaries for each store and all stores.
  - Insights from the analyses of the movement of the products, including the best-selling and the most profitable products.
  - Stock levels for each store.
- A **Client page** for customers to check out products of the grocery stores, including the following functions:
  - See the products by category and by store with their price and availability.
  - A Chatbot to help customers with their enquiries.

# My contribution

- Actively participated in brainstorming sessions to generate ideas and suggestted solutions for the app's functionalities
- Developed and implemented app functions to automatically send alert emails for low-stock and nearly expired products using `Node-RED`
- Collaborated with team members in building a Chatbot using IBM Watson Assistant
- Created and edited demo video using iMovie to showcase the app's features and capabilities
- Maintained open communication with team members, regularly providing updates and feedback to ensure project success.

# Source code

Unfortunately, this is a uni project and the source code **cannot be shared** due to academic integrity and intellectual property concerns.
