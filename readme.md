


* update site snippit list
* add site snippet editor
* refresh admin
* add content



```

require(['modules/api'], function(api){ window.mozuApi = api})

mozuApi.get('documentView', {listName:'siteSnippets@mozu' , filter:'name eq drop-ship.html'}).then(x=> console.log(JSON.stringify(x.data.items)))

```