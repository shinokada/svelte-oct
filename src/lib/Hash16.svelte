<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'hash 16';
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
    d="M6.368 1.01a.75.75 0 0 1 .623.859L6.57 4.5h3.98l.46-2.868a.75.75 0 0 1 1.48.237L12.07 4.5h2.18a.75.75 0 0 1 0 1.5h-2.42l-.64 4h2.56a.75.75 0 0 1 0 1.5h-2.8l-.46 2.869a.75.75 0 0 1-1.48-.237l.42-2.632H5.45l-.46 2.869a.75.75 0 0 1-1.48-.237l.42-2.632H1.75a.75.75 0 0 1 0-1.5h2.42l.64-4H2.25a.75.75 0 0 1 0-1.5h2.8l.46-2.868a.75.75 0 0 1 .858-.622ZM9.67 10l.64-4H6.33l-.64 4Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'hash 16';
-->
