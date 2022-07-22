<script lang="ts">
	export let size = '16';
	export let color = 'currentColor';
	export let ariaLabel = 'x circle fill 12';
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	{...$$restProps}
	aria-label={ariaLabel}
	viewBox="0 0 12 12"
	><path
		fill-rule="evenodd"
		d="M1.757 10.243a6 6 0 118.486-8.486 6 6 0 01-8.486 8.486zM6 4.763l-2-2L2.763 4l2 2-2 2L4 9.237l2-2 2 2L9.237 8l-2-2 2-2L8 2.763l-2 2z"
	/></svg
>
