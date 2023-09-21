<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'feed pull request closed 16';
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
    d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM5.5 12.25A1.75 1.75 0 0 0 6 8.822V6.928A1.752 1.752 0 0 0 5.5 3.5 1.75 1.75 0 0 0 5 6.928v1.894a1.752 1.752 0 0 0 .5 3.428Zm5-5a.5.5 0 0 0-.5.5v1.072a1.752 1.752 0 0 0 .5 3.428 1.75 1.75 0 0 0 .5-3.428V7.75a.5.5 0 0 0-.5-.5Zm1.255-2.763a.5.5 0 0 0-.707-.707l-.53.531-.531-.531a.5.5 0 0 0-.707.707l.531.531-.531.53a.5.5 0 0 0 .707.707l.531-.53.53.53a.5.5 0 0 0 .707-.707l-.53-.53Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'feed pull request closed 16';
-->
