<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'pulse 24';
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
    d="M9.002 2.5a.75.75 0 0 1 .691.464l6.302 15.305 2.56-6.301a.75.75 0 0 1 .695-.468h4a.75.75 0 0 1 0 1.5h-3.495l-3.06 7.532a.75.75 0 0 1-1.389.004L8.997 5.21l-3.054 7.329A.75.75 0 0 1 5.25 13H.75a.75.75 0 0 1 0-1.5h4l3.558-8.538a.75.75 0 0 1 .694-.462Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'pulse 24';
-->
