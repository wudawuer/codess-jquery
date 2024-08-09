## jqNamespace
#### jqNamespace
A namespace template. ref: http://enterprisejquery.com/2010/10/how-good-c-habits-can-encourage-bad-javascript-habits-part-1/
```javascript
(function ( ${name}, $, undefined ) {
	// Private Property
	myPrivateProperty = "Private Property";
		
	// Public Property
	${name}.myPublicProperty = "Publically Accessible Property";
		
	// Private Method
	function myPrivateMethod () {
		
	}
		
	// Public Method
	${name}.myPublicMethod = function () {
		
	};  
}(window.${name} = window.${name} || {}, jQuery ));
```