# jQuery Exercise 4

## Fetch latest Repository Branch

```
$ cd /DRIVE/xampp/htdocs/jQuery
$ git pull --no-edit https://github.com/noucampdotorgRESTAPIAPPLIED/jQuery.git latest
$ git status

```


# Part 1 – Ajax get() Method


1.	Examine and then run the code in [http://localhost/jQuery/AjaxGet.html](http://localhost/jQuery/AjaxGet.html) to demonstrate jQuery using the Ajax function ``get()``.

1.	Create a new file called ``MyAjaxData.txt`` and add some basic HTML tag data to it, e.g. a ``<ol>`` or ``<table>``.  Then modify the ``AjaxGet.js`` program to load and show it.
	
1.	Add to the HTML page ``DropdownjQueryAjax.html`` a dropdown box that has options for:

	```
	Choose type...
	Goalkeepers
	Defenders
	Midfielders
	Forwards 

	```

	Write the jQuery code in a JavaScript file ``DropdownjQueryAjax.js`` that retrieves the appropriate data for the player type selected from either of the corresponding files -- ``goalkeepers.txt``, ``defenders.txt``,
	``midfielders.txt`` and ``forwards.txt`` - and displays that data on the HTML page. 
	

1.	Push your code to **your private** repository on GitHub.  Type these commands into your *Git Bash* client:

	```
	$ git status
	$ git add .
	$ git commit -m "Exercise 4 - Part 1 DONE|PARTIAL|HELP"
	$ git push origin master
	$ git status

	```


# Part 2 – Ajax getJSON() Method

1.	Examine and then run the code in [http://localhost/jQuery/AjaxGetJSON.html](http://localhost/jQuery/AjaxGetJSON.html) to demonstrate jQuery using the Ajax function ``getJSON()``.


1.	Examine and then run the code in [http://localhost/jQuery/getArtistsJSON.php](http://localhost/jQuery/getArtistsJSON.php) to retrieve artist JSON data from the ``music`` database.


1.	Examine the code in [http://localhost/jQuery/Artists.html](http://localhost/jQuery/Artists.html).  It has a JavaScript file called ``Artists.js`` that will retrieve JSON artist data using ``getArtistsJSON.php``.


1.	Write the jQuery code in  ``Artists.js`` to retrieve the JSON artist data from ``getArtistsJSON.php`` and display just the artist names in ``Artists.html`` like this:

	```
	New Order
	Nick Cave & The Bad Seeds
	Miles Davis
	The Rolling Stones
	The Stone Roses
	Kylie Minogue

	```

1.	Push your code to **your private** repository on GitHub.  Type these commands into your *Git Bash* client:

	```
	$ git status
	$ git add .
	$ git commit -m "Exercise 4 - Part 2 DONE|PARTIAL|HELP"
	$ git push origin master
	$ git status

	```