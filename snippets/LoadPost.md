## LoadPost
#### jqLoadPost
Load data from the server and place the returned HTML into the matched element.
```
$(${selector}).load("${url}", "${data}", function (response, status, request) {
	this; // dom element
	$0
});
```