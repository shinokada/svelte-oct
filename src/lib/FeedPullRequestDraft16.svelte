<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'feed pull request draft 16';
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
    d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm7.25 2.5c0-.793-.527-1.462-1.25-1.678V6.928A1.752 1.752 0 0 0 5.5 3.5 1.75 1.75 0 0 0 5 6.928v1.894a1.752 1.752 0 0 0 .5 3.428 1.75 1.75 0 0 0 1.75-1.75Zm3.25 1.75a1.75 1.75 0 1 0 .001-3.499 1.75 1.75 0 0 0-.001 3.499Zm0-4.5a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm.75-3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'feed pull request draft 16';
-->
