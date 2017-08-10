# vallenato.js
A simple jquery accordion to spice up your website content.

## Dependencies
This script requires jQuery to function.

## Setup
Link to the css and js files:

```html
<link rel="stylesheet" href="vallenato.css">

<script src="jquery.js"></script>
<script src="vallenato.js"></script>
```

## Structure
Setup your html like code in the example below:

```html
<div class="vallenato">
	<div class="vallenato-header">
		Header 1
	</div><!--/.vallenato-header-->

	<div class="vallenato-content">
		Your Content...
	</div><!--/.vallenato-content-->

	<div class="vallenato-header">
		Header 2
	</div><!--/.vallenato-header-->

	<div class="vallenato-content">
		Your Content...
	</div><!--/.vallenato-content-->
</div><!--/.vallenato-->```

## Run the Function
Simply add the vallenato() function to your site to enable the accordion.

```javascript
<script>
	$(document).ready(function() {
		vallenato();
	});
</script>
```
