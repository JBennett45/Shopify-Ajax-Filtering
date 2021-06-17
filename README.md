# Filter Shopify Products With Tags
Shopify Ajax collection page powered by product tags. Supporting category filtering and load more endless scroll.

### Application ###
The collection-main.liquid file is what you'd use in your theme for the collections page/where you want the Ajax filtering to appear. Theres very basic styling in the style.css file and the Ajaxinate script is included too (see third party scripts below).

### Making the tags work ###
Use the method of tag-your content, you will be able to pull things through, in my example the categories are brands, colours and price. So brands for example need to be tagged within Shopify as `<strong>`brands-Hollister`</strong>` in order for Hollister to then appear in the sidebar and filter down for that product on click.

#### Third party scripts ####
In this repo you'll find the most recent Ajaxinate script needed to make this all tick (17/06/2021). You'll also need to make sure your theme has jQuery support.

##### Credit #####
I originally took the code from Lysindr and edited it to be multiple/categorised tags rather than one list but credit to them for first getting the ajax functionality working.

[Original Repo](https://gist.github.com/Lysindr/87ea06eb017a2bc58e2f9ed057b27d0f)
