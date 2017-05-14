<h1>Two Tone Documentation</h1>

<h2>Total Dark Mode</h2>

```
<body class="dark">
```

<h2>Standard Navigation</h2>

```
<div class="nav"> <!-- Dark Mode: <div class="nav dark"> -->
	<ul>
		<a href="#" class="nav-logo">Website Name</a>
		<a href="#">Item #1</a>
		<a href="#">Item #2</a>
		<a href="#">Item #3</a>
		<a href="#">Item #4</a>
		<a href="#">Item #5</a>
		<div class="dropdown">
		  	<a href="#">Dropdown #1</a>
		  	<div class="dropdown-content">
		    	<a href="#">Item #1</a>
		    	<a href="#">Item #2</a>
		    	<a href="#">Item #3</a>
		  	</div>
		</div>
	</ul>
</div>
```

<h2>Mobile Navigation</h2>

```
<div class="mob-nav"> <!-- Dark Mode: <div class="mob-nav dark"> -->
	<input type="checkbox">
	<span></span>
	<span></span>
	<span></span>
	<ul class="mob-menu">
		<a href="#"><li>Item #1</li></a>
		<a href="#"><li>Item #2</li></a>
		<a href="#"><li>Item #3</li></a>
		<a href="#"><li>Item #4</li></a>
		<a href="#"><li>Item #5</li></a>
	</ul>
</div>
```

<h2>Multiple Sections</h2>

```
<div class="sec"> <!-- Dark Mode: <div class="sec dark"> -->
	...
</div>

<div class="sec">
	...
</div>

<div class="sec">
	...
</div>
```

<h2>Variable Width Columns</h2>

```
<ul class="col"> <!-- Dark Mode: <ul class="col dark"> -->
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<!-- Can add more <li> for more columns -->
</ul>
```

<h4>Column options</h4>

```
<ul class="col pd"> <!-- Spacing -->
<ul class="col center"> <!-- Centered text -->
<ul class="col clear"> <!-- Transparent Columns -->
<ul class="col dark"> <!-- Dark theme -->
<ul class="col pd dark center"> <!-- Combinations are available -->
```

<h2>Padding/Margin Options</h2>

```
<!-- Add 15px margins to every element by adding the pd class -->
<input class="pd">
<ul class="col pd"></ul>
```