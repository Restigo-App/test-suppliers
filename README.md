<p align="center"><img src="https://app.restigo.co.il/img/logo-dark.png" width="400"></p>



<h2>About Restigo</h2>

<h2>Suppliers Test</h2>
Application for supplier to manage catalog items, clients and relation between them.

Required tables and basic fields (you can add table or fields if necessary)

'items' table :
<pre>
-name
-catalog_number [unique]
-price
-has_vat
-enable
</pre>



'clients' table :
<pre>
-name [unique]
-type (1-resturant;2-coffe house;3-bar)
-enable
</pre>

'diversities' table :
<pre>
-name [unique]
-enable
</pre>



Each Diversity could have multiple item and multiple clients assigned.

<h3><u>Pages:</u></h3>
<strong>Items Manager</strong>
<ul>
    <li>user can add item</li>
    <li>Show table of all items</li>
    <li>user can edit item from table, can assign one or more diversities to the item</li>
</ul>
<strong>Clients Manager</strong>
<ul>
    <li>user can add client</li>
    <li>Show table of all clients</li>
    <li>user can edit client from table, can assign one or more diversities to the client</li>
</ul>
<strong>Diversities Manager</strong>
<ul>
    <li>user can add diversity</li>
    <li>Show table of all diversities, with assigned items and clients count</li>
    <li>user can edit diversity from table, can remove item or client</li>
</ul>



  

