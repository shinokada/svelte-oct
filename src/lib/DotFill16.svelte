<script lang="ts">
	export let size = '16';
	export let color = 'currentColor';
	export let ariaLabel = 'dot fill 16';
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	{...$$restProps}
	aria-label={ariaLabel}
	viewBox="0 0 16 16"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z" /></svg
>
