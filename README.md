# Use
```scss
aside {
	float: left;
	width: 300px;
	@include responds-to(tablet, true) {
		width: 240px;
	}
	@include responds-to(mobile) {
		float: none;
		width: 100%;
	}
}
```

You can also specify multiple sizes:
```scss
#content {
	width: 960px;
	@include responds-to(tablet small-tablet) { width: 600px; }
}
```