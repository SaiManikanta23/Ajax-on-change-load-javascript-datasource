# Ajax-on-change-load-javascript-datasource
This program gives an about how to load java scipt datasource to div container automatically using ajax. 
This is helpful when the div data is huge and needed to be loaded only on selection rather than loading along with page load which makes the page to load slower as it takes lot of time to completely load all the div contents.


In this example, I am considering a selection box with 500 option with each option it loads a div, i.e. here we have about 500 divs along with 500 select options

The data for div is stored in javascript datasource and is loaded only when we select the respective option.

When we select the 1st option, then the first datasource is loaded similiarly 2nd and so on. The data source is stored in variable to_display in the javascript datasource and is stored as list seperated by commas.

Later on select we append the option to the select box as numbers i.e. from 1 to 500. For each option the list is loaded respectively based on index.

When the option value is 0 the first index value is loaded similarly for others  which can be seen in the script, where we use a for loop and increment the index and option value as loop runs and load each data respectively according to index values and display the content using to_display function.

We can either use on 'change' or on 'click' function. With on change the data gets loaded after selecting the option from dropdown, where as with click the data starts loading with cick on the option i.e before even selecting the option so choose the event wisely. In this example i have used on change. And we can either use html or text as the data. If the data in datasource is html content like iframes, html data etc we can use .html as used in the example or we can use .text for simple text in each of the contents
