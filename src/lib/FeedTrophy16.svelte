<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'feed trophy 16';
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
  ><path
    d="M11 5h1v1.146a1 1 0 0 1-.629.928L11 7.223V5ZM5 7.223l-.371-.149A1 1 0 0 1 4 6.146V5h1v2.223Z"
  /><path
    d="M8 16A8 8 0 1 1 8 0a8 8 0 0 1 0 16ZM3 5v1.146a2 2 0 0 0 1.257 1.858l.865.346a3.005 3.005 0 0 0 2.294 2.093C7.22 11.404 6.658 12 5.502 12H5.5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1c-1.158 0-1.72-.595-1.916-1.557a3.005 3.005 0 0 0 2.294-2.094l.865-.346A2 2 0 0 0 13 6.146V5a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'feed trophy 16';
-->
