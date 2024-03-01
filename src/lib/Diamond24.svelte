<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'diamond 24';
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
  viewBox="0 0 24 24"
  ><path
    d="M1.527 13.237a1.75 1.75 0 0 1 0-2.474l9.272-9.273a1.75 1.75 0 0 1 2.475 0l9.272 9.273a1.75 1.75 0 0 1 0 2.474l-9.272 9.272a1.75 1.75 0 0 1-2.475 0Zm1.06-1.414a.25.25 0 0 0 0 .354l9.273 9.272a.25.25 0 0 0 .353 0l9.272-9.272a.25.25 0 0 0 0-.354l-9.272-9.272a.25.25 0 0 0-.353 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'diamond 24';
-->
