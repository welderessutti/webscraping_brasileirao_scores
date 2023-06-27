<h1>Webscraping Brasileirão Scores stored into MySQL Database</h1>

<h2>Webscraping</h2>
<p>This is a webscraping script of the UOL website to obtain Brasileirão scores and load them into a MySQL database.</p>
<p>This script uses Python libraries like Selenium, BS4, Pandas, Numpy, JSON, Datetime and MySQL Connector.</p>
<p>It sends a request to UOL website, which has a Brasileirão scores table. It gets website HTML content and scraps the data of the teams from the table, appending all of them into the lists.</p>
<p>Using the Pandas Lib, it´s created a dataframe and the lists are converted into a dictionary.</p>
<p>At last, the dictionary is converted into a JSON file and saved in the directory.</p>

<h2>Storing into MySQL</h2>
<p>Using the MySQL Connector lib, it´s created a connection and the cursor.</p>
<p>After, it´s created a database named of "brasileirao", a table with the same name of the JSON file and its columns.</p>
<p>At last, the JSON file is opened and all of its dataset is inserted into the table.</p>

<p>*Project under development.</p>
