# Use
```scss
aside {
	float: left;
	width: 320px;
	@include responds-to(desktop) {
		float: none;
		width: 100%;
	}
}
```