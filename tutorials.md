# Write a slides with Reveal.js
### Here we use markdown syntax

<small>Created by [Shawn Huang](#) / [@_shawnhuang](#)</small>



## Layout

```
## Title

content

content
```


## Two Columns

<div markdown="1" class="left-column">
## Column 1
```
<div markdown="1" 
class="left-column">
</div>
```
</div>

<div markdown="1" class="right-column">
## Column2
```
<div markdown="1" 
class="right-column">
</div>
```
</div>

<div style="clear:both;" />

```
<div style="clear:both;" />
```


<div markdown="1" class="left-column">
## Column 1
![test](http://static.independent.co.uk/s3fs-public/thumbnails/image/2013/01/24/12/v2-cute-cat-picture.jpg) <!-- .element:  -->
</div>

<div markdown="1" class="right-column">
![test](http://static.independent.co.uk/s3fs-public/thumbnails/image/2013/01/24/12/v2-cute-cat-picture.jpg) <!-- .element:  -->
</div>

<div style="clear:both;" />


## Image
![test](http://static.independent.co.uk/s3fs-public/thumbnails/image/2013/01/24/12/v2-cute-cat-picture.jpg) <!-- .element: width="450px"  -->


![test](http://static.independent.co.uk/s3fs-public/thumbnails/image/2013/01/24/12/v2-cute-cat-picture.jpg) <!-- .element: width="450px"  -->
## Image


<!-- .slide: style="text-align:left" -->
# One
# Two
# Three



## Fragments
- `text<!-- .element: class="fragment" data-fragment-index="7" -->`<!-- .element: class="fragment" data-fragment-index="1" style="font-size:18px" -->
- fragment<!-- .element: class="fragment" data-fragment-index="7" -->
- grow<!-- .element: class="fragment grow" data-fragment-index="8" -->
- shrink<!-- .element: class="fragment shrink" data-fragment-index="3" -->
- fade-out<!-- .element: class="fragment fade-out" data-fragment-index="4" -->
- current-visible<!-- .element: class="fragment current-visible" data-fragment-index="6" -->
- highlight-red<!-- .element: class="fragment highlight-red" data-fragment-index="5" -->
- ```
	<div markdown="1" class="fragment"
			 data-fragment-index="2"
			 style="position:absolute;
			 top:300px;right:100px;width:20%;">
	![test](name.jpg)
	</div>
	```

<div markdown="1" class="fragment" data-fragment-index="2" style="position:absolute;top:300px;right:100px;width:20%;">
![test](http://static.independent.co.uk/s3fs-public/thumbnails/image/2013/01/24/12/v2-cute-cat-picture.jpg)
</div>



## Shortcuts 

- overview
	* 按 `Esc` 即可

- speaker note
	* 按 `s` 即可

	```
	Note:
	做筆記區塊
	```

- pause
	* 按 `b` 即可

Note:
做筆記區塊



<!-- .slide: data-state="something" -->
## Data-state

```
data-state="something"
```

```
Reveal.addEventListener( 'customevent', function() {
		console.log( '"customevent" has fired' );
		} );
}
```



<!-- .slide: data-background="#dddddd" -->
## Background

```
<!-- .slide: data-background="#dddddd" -->
```


<!-- .slide: data-background="https://s3.amazonaws.com/hakim-static/reveal-js/image-placeholder.png" -->
## Background with image

```
<!-- .slide: data-background="bg.jpg" 
data-background-repeat="repeat" data-background-size="100px"-->
```


<!-- .slide: data-background-video="https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.mp4,https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.webm" data-background-color="#000000" -->
## Background with Videos
```
<!-- .slide: data-background-video="https://.../*.mp4,https://.../*.webm"
data-background-color="#000000" -->
```


<!-- .slide: data-transition="slide" data-background="#4d7e65" data-background-transitin="zoom" -->
## Background transition

```
<!-- .slide: data-transition="slide" 
data-background="#4d7e65" data-background-transitin="zoom" -->
```


<!-- .slide: data-transition="slide" data-background="#b5533c" data-background-transitin="zoom" -->
## Background transition

```
<!-- .slide: data-transition="slide"
data-background="#4d7e65" data-background-transitin="zoom" -->
```



## Code

	```js
	function linkify( selector ) {
		if( supports3DTransforms ) {

			var nodes = document.querySelectorAll( selector );

			for( var i = 0, len = nodes.length; i &lt; len; i++ ) {
				var node = nodes[i];

				if( !node.className ) {
					node.className += ' roll';
				}
			}
		}
	}
	```



## List

- test
- test
- test

```
- test
- test
- test
```


## Order List

1. test
2. test
3. test

```
1. test
2. test
3. test
```



## Table

|a  |b  |
|:-:|:--|
|c  |d  |

```
|center  |left  |
|:------:|:-----|
|c       |d     |
```



## Quote

> &ldquo;text&rdquo;

```
> &ldquo;text&rdquo;
```



## Math

$$x = {-b \pm \sqrt{b^2 -4ac} \over 2a}$$

```
$$x = {-b \pm \sqrt{b^2 -4ac} \over 2a}$$
```
