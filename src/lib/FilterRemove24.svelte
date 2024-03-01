<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'filter remove 24';
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
    d="M21.587 9.273a.75.75 0 1 0 1.061-1.061l-1.591-1.591 1.591-1.591a.749.749 0 1 0-1.061-1.06l-1.591 1.591-1.591-1.591a.749.749 0 1 0-1.06 1.06l1.591 1.591-1.591 1.591a.75.75 0 0 0 1.06 1.061l1.591-1.591 1.591 1.591ZM1.75 6a.75.75 0 0 0 0 1.5H14.5a.75.75 0 0 0 0-1.5H1.75ZM5 11.75a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 0 1.5H5.75a.75.75 0 0 1-.75-.75Zm4 4.938a.75.75 0 0 1 .75-.75h2.5a.75.75 0 1 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'filter remove 24';
-->
