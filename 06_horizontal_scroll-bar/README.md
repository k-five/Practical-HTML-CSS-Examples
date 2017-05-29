### 06_horizontal_scroll-bar  

You will learn how to implement a horizontal scrollbar. Although  
implementing a vertical one is so easy, but for a horizontal one  
we have to use a little bit complex code.  

The main idea is based on unordered-list `ul` and list `li`  

try this:  
  
```HTML  
	<div class="content">
		<ul>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
			<li>some text</li>
		</ul>
	</div>

```  

and   

```CSS  
div.content{
	width: 400px;
	height: 100px;
	border: 1px red solid;

	overflow-x: scroll;
	overflow-y: hidden;
}
ul{
	white-space: nowrap;
}
li{
	display: inline-block;
	list-style-type: none;
}

```

screenshot:

[screenshot](https://github.com/k-five/Practical-HTML-CSS-Examples/tree/master/06_horizontal_scroll-bar/06_page_screenshot)  