## Plugin
#### jqPlugin
Plugin template.
```
(function ($) {
	jQuery.fn.${pluginName} = function (settings) {
		var config = {'foo': 'bar'};
 
		if (settings) jQuery.extend(config, settings);
 
		this.each(function () {
			// element-specific code here
			$0
		});
 
		return this;
	};
})(jQuery);
```