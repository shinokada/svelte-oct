<script lang="ts">
	export let size = '16';
	export let color = 'currentColor';
	export let ariaLabel = 'horizontal rule 24';
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	{...$$restProps}
	aria-label={ariaLabel}
	viewBox="0 0 24 24"
	><path
		fill-rule="evenodd"
		d="M2 12.75a.75.75 0 01.75-.75h18.5a.75.75 0 010 1.5H2.75a.75.75 0 01-.75-.75z"
	/></svg
>
