# Use
```scss
aside {
	float: left;
	width: 300px;
	@include responds-to(tablet, true) {
		float: none;
		width: 240px;
	}
	@include responds-to(mobile) {
		float: none;
		width: 100%;
	}
}
```