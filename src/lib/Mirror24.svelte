<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'mirror 24';
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
    d="M21.553 6.064A.75.75 0 0 1 22 6.75v10.5a.75.75 0 0 1-1.256.554l-5.75-5.25a.748.748 0 0 1 0-1.108l5.75-5.25a.75.75 0 0 1 .809-.132ZM2.447 17.936A.75.75 0 0 1 2 17.25V6.75a.75.75 0 0 1 1.256-.554l5.75 5.25a.748.748 0 0 1 0 1.108l-5.75 5.25a.75.75 0 0 1-.809.132ZM7.387 12 3.5 8.45v7.1L7.388 12Zm9.226 0 3.887 3.55v-7.1L16.612 12ZM12 2.75a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75Zm0 4a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75Zm0 8a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75Zm0 4a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75Zm0-8a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'mirror 24';
-->
