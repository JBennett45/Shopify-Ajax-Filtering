# Filter Shopify Products With Tags
Shopify Ajax collection powered and populated by product tags, supporting category filtering and load more endless scroll.

### Application ###
The collection-main.liquid file is what to use in your theme where you want the Ajax filtering to appear. Theres very basic styling (in style.css) and the Ajaxinate script is included (see third party scripts below).

### Making the tags work ###
Use the prefix of 'tag-your content' to pull things through, in my example the categories are brands, colours and price. So for example brands would need to be tagged within the Shopify product as **brands-Hollister** in order for 'Hollister' to then appear in the sidebar, then when that brands is click any product with that brand tag will appear.

#### Third party scripts ####
In this repo you'll find the most recent Ajaxinate script(17/06/2021) needed to make this all tick. You'll also need to **make sure your theme has jQuery support**.

##### Credit #####
I originally took the code from Lysindr and edited it to be multiple/categorised tags rather than one list but credit to them for first getting the ajax functionality working.

[Original Repo](https://gist.github.com/Lysindr/87ea06eb017a2bc58e2f9ed057b27d0f)
