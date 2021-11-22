# a3-collection-prototype

As of now this prototype does not properly make calls to the server.



## How to run locally

### Dependencies

* yarn (npm should be fine but there is no package-lock.json provided)

### Steps

* clone respository
* cd into root folder
* `yarn` or `npm install` to install dependencies
* `yarn dev` or `npm run dev` to start the app in dev mode
* visit http://localhost:3000 in browser



## Brief Run-through

### Add collection page

* fill out fields with collection information
* creating new item takes user to add items page from a1
* upon creating new item, takes user back to collection page and lists the new item in current collection items
* allows for continuous item addition to collection until submittal

### Editing collections

* visit /creator_view to view better creator interface
* click Collections View to view existing collections
* click edit to edit a collection
* takes user back to add collection page with pre-populated data
* user can make changes then resubmit the collection with updates

