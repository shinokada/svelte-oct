<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'feed tag 16';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
  on:click
  on:keydown
  on:keyup
  on:focus
  on:blur
  on:mouseenter
  on:mouseleave
  on:mouseover
  on:mouseout
  viewBox="0 0 16 16"
  ><path d="M7.22 6.5a.72.72 0 1 1-1.44 0 .72.72 0 0 1 1.44 0Z" /><path
    d="M8 16A8 8 0 1 1 8 0a8 8 0 0 1 0 16ZM4 5v3.38c.001.397.159.778.44 1.059l3.211 3.213a1.202 1.202 0 0 0 1.698 0l3.303-3.303a1.202 1.202 0 0 0 0-1.698L9.439 4.44A1.5 1.5 0 0 0 8.379 4H5a1 1 0 0 0-1 1Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'feed tag 16';
-->
