<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'diff 24';
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
    d="M12.25 3.5a.75.75 0 0 1 .75.75V8.5h4.25a.75.75 0 0 1 0 1.5H13v4.25a.75.75 0 0 1-1.5 0V10H7.25a.75.75 0 0 1 0-1.5h4.25V4.25a.75.75 0 0 1 .75-.75ZM6.562 19.25a.75.75 0 0 1 .75-.75h9.938a.75.75 0 0 1 0 1.5H7.312a.75.75 0 0 1-.75-.75Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'diff 24';
-->
