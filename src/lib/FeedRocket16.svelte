<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'feed rocket 16';
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
    d="M8 16A8 8 0 1 1 8 0a8 8 0 0 1 0 16Zm3.031-12a4.38 4.38 0 0 0-3.097 1.283l-.23.229c-.156.157-.308.32-.452.49H5.65a.876.876 0 0 0-.746.417l-.856 1.388a.377.377 0 0 0 .21.556l1.552.477 1.35 1.35.478 1.553a.374.374 0 0 0 .555.21l1.389-.855a.876.876 0 0 0 .416-.746V8.747c.17-.144.333-.295.49-.452l.23-.23A4.379 4.379 0 0 0 12 4.969v-.093A.876.876 0 0 0 11.124 4Zm-5.107 7.144h-.001a.809.809 0 0 0-1.33-.881c-.395.394-.564 1.258-.62 1.62a.12.12 0 0 0 .035.108.12.12 0 0 0 .108.035c.362-.056 1.226-.225 1.62-.619a.803.803 0 0 0 .188-.263Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'feed rocket 16';
-->
