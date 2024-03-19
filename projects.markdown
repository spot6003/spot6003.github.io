---
layout: page
title: "Projects"
permalink: "/projects"
---

<h2>Course Project: ETools Purchasing System </h2>
<p>This app programmed in the C Sharp language is meant to be used by the purchasing department
of the fictional "ETools" company. The purchasing section let managers generate a new purchase order,
retrieve an existing purchase order, or place the order as shown below. There are multiple companies
eTools can place a purchase order with.</p>
<img src="img/etoolsscreenshot1.png">
<p>If you were to select the vendor as Nuts, Bolts and Fasteners the following purchase order will be brought up</p>
<img src="img/etoolsscreenshot2.png">
<p>Upon selecting a vendor, the purchase order number and vendor information populate and the user presses the update button.
If a vendor is not selected an error message will be displayed to the user. Once the update button is pressed the items on the order
will populate the table. This table provides information about each item and their stock levels. If a manager does not want to order
a specific item, clicking the trash can icon will remove it from the order. Pressing the recalc button will update the price field. Below this table is the vendor's stock items that are currently not on the order as shown below.</p>
<img src="img/etoolsscreenshot3.png">
<p>This table shows almost the same information the previous table does, with one exception. The buffer value shows how many items are left
before the reorder threshold is reached. The add button allows the manager to add the item to the current purchase order.</p>


<p>Skills Used</p>
<ul>
    <li>Blazor Framework utilizing C Sharp</li>
    <li>SQL</li>
    <li>HTML & CSS</li>
</ul>

<h2>Course Assignment: Stock App</h2>
<p>This app programmed in the Dart language lets users search up a stock symbol and then save the stock information to a database that lets the user see the information as many times as they want until they delete the database.</p>
<img src="img/dartscreenshot1.png">
<p>When the user taps the Add Stock button, an input menu pops up and prompts the user to enter the stock symbol for the stock they want information for. In this case, we are searching for Walmart Inc. as shown below.</p>
<img src="img/dartscreenshot2.png">
<p>Upon tapping the add stock button in the input menu, the app makes a call to a REST API and brings back information about the searched stock, saves, then displays the information to the user. The information saved in the database does not change after the original call so if the user wants updated information they will need to use the add stock button again. The result of this process is shown below</p>
<img src="/img/dartscreenshot3.png">


<p>Skills Used</p>
<ul>
    <li>Flutter Framework utilizing Dart</li>
    <li>REST API call</li>
</ul>