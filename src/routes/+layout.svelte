<script lang="ts">
	let { children } = $props();
</script>

<nav>
  <a href="/about">About Me</a>
  <a href="/projects">Projects</a>
</nav>

{@render children()}
