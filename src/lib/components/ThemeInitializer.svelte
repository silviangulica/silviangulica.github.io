<script>
		window.prefersDarkmode = false;
    let dark = localStorage.getItem("theme");

    if (dark) {
      document.documentElement.setAttribute("data-theme", "dark");
    } else {
      document.documentElement.setAttribute("data-theme", "cupcake");
    }
	</script>
<slot />
