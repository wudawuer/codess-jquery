## AjaxAspNetWebService
#### jqAjaxAspNetWebService
Perform an asynchronous HTTP (Ajax) request to a ASP.NET web service.
```
$.ajax({
	type: "POST",
	contentType: "application/json; charset=utf-8",
	dataType: "${dataType}",
	url: "${url}",
	data: "${data}",
	success: function (response) {
		$0
	}
});
```