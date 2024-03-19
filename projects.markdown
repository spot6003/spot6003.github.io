---
layout: page
title: "Projects"
permalink: "/projects"
---

<p>This project list is subject to change. Check back often to see the new things I've been working on!</p>

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

<h2>Course Assignment: Custom REST API using Java</h2>
<p>This app was programmed using Java to implement a custom REST API that I created based on NHL player stats for some Edmonton Oilers players.
The backend and frontend aspects of this project were both implemented by me. Upon starting the app, you will encounter this page seen below. This project implements create, read, update, and delete (CRUD) principles</p>
<img src="/img/javascreenshot1.png">
<p>When the app starts, the site uses the read operation to get data from the REST API to display it to the user. From this page, the user can either create a new player stat, edit an existing one, check more details about the stat, or delete the stat.</p>
<img src="/img/javascreenshot2.png">
<p>The image above shows the page the user navigates to upon pressing create. Here they enter the required information and then press create.
The inputted data must meet certain requirements and the page will not allow a new entity to be created till the requirements are met. Upon
successful creation a success message is shown on the list page. This process is similar to the edit page, shown below</p>
<img src="/img/javascreenshot3.png">
<p>Like the create page, the user sends in information that must meet requirements but this time the user may change zero, one, or many of the
entity's fields. When the edit has been completed, a success message is shown on the list page.</p>
<img src="img/javascreenshot4.png">
<p>The final operation that can be done on the app is deleting an entity. When a user presses delete on the list page, they are shown the information marked for deletion. Upon pressing the delete button below all the details, a final dialogue appears asking if the user is sure
they want to delete the entity. If the user confirms yes, the entity is deleted and a success message is shown on the list page. All of the above pages also have a link to navigate the user back to the list page.</p>

<p>Skills Used</p>
<ul>
    <li>REST API implementation using Java</li>
    <li>HTML with PrimeFaces</li>
</ul>


<h2>Course Assignment: React and REST APIs</h2>
<p>This app was programmed using Javascript to provide a user with a list of authors and their respective books. This information is retrieved from a REST API along with their date of birth and date of death if applicable. Clicking the Details button next to the book routed the user to a new page with the book's title, and all covers if the REST API returned any</p>
<img src="img/javascriptscreenshot1.png">
<p>If the user wants to check out the details of a different author, they would find that author in the author's list and press the show button. A request is sent to the REST API and all the site's data is updated through React State and it's useEffect method. An example using J.R.R Tolkien is shown below
<img src="img/javascriptscreenshot2.png">
<p>The result of clicking on the details button of a book as discussed above is shown below</p>
<img src="img/javascriptscreenshot3.png">

<p>Skills Used</p>
<ul>
    <li>React library using Javascript</li>
    <li>REST API implementation through Javascript</li>
    <li>Page routing using Javascript</li>
</ul>