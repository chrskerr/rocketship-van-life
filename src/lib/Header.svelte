<script>
	const pathname = window.location.pathname;
</script>

<!-- Header -->
<header id="header">
	<a href="index.html" class="logo">Massively</a>
</header>

<!-- Nav -->
<nav id="nav">
	<ul class="links">
		<li class={pathname === "/" ? "active" : ""}>
			<a href="/">This is Massively</a>
		</li>
		<li class={pathname === "/generic" ? "active" : ""}>
			<a href="/generic">Generic Page</a>
		</li>
		<li class={pathname === "/elements" ? "active" : ""}>
			<a href="/elements">Elements Reference</a>
		</li>
	</ul>
	<ul class="icons">
		<li>
			<a href="#" class="icon brands fa-twitter"
				><span class="label">Twitter</span></a
			>
		</li>
		<li>
			<a href="#" class="icon brands fa-facebook-f"
				><span class="label">Facebook</span></a
			>
		</li>
		<li>
			<a href="#" class="icon brands fa-instagram"
				><span class="label">Instagram</span></a
			>
		</li>
		<li>
			<a href="#" class="icon brands fa-github"
				><span class="label">GitHub</span></a
			>
		</li>
	</ul>
</nav>
