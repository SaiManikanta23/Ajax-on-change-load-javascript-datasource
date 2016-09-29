# Ajax-on-change-load-javascript-datasource
This program gives an about how to load java scipt datasource to div container automatically using ajax. 
This is helpful when the div data is huge and needed to be loaded only on selection rather than loading along with page load which makes the page to load slower as it takes lot of time to completely load all the div contents.


In this example, I am considering a selection box with 500 option with each option it loads a div, i.e. here we have about 500 divs along with 500 select options

The data for div is stored in javascript datasource and is loaded only when we select the respective option.

When we select the 1st option, then the first datasource is loaded similiarly 2nd and so on. The data source is stored in var and is stored as list seperated by commas.
