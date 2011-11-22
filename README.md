Raphael.FreeTransform
====================

  Free transform tool Raphaël elements.

  ![Screenshot](https://github.com/ElbertF/Raphael.FreeTransform/raw/master/screenshot.png)


Example
-------

```html
<script type="text/javascript" src="raphael-min.js"></script>
<script type="text/javascript" src="raphael.free_transform.js"></script>

<div id="foo"></div>

<script type="text/javascript">
	var paper = Raphael('foo');

	var rect = paper
		.rect(50, 40, 50, 50)
		.attr('fill', '#f00')
		;

	// Add free transform handle
	paper.freeTransform(rect);

	console.log(rect);

	// Remove free transform handle
	// paper.freeTransform(rect).unplug();
</script>
```
