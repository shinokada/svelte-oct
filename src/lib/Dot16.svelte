<script lang="ts">
	export let size = '16';
	export let color = 'currentColor';
	export let ariaLabel = 'dot 16';
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	{...$$restProps}
	aria-label={ariaLabel}
	viewBox="0 0 16 16"
	><path
		fill-rule="evenodd"
		d="M8 5.5a2.5 2.5 0 100 5 2.5 2.5 0 000-5zM4 8a4 4 0 118 0 4 4 0 01-8 0z"
	/></svg
>
