<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'fold 24';
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
    d="M12 15c.199 0 .389.079.53.22l3.25 3.25a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L12 16.81l-2.72 2.72a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.25-3.25A.749.749 0 0 1 12 15Z"
  /><path
    d="M12.53 8.78a.75.75 0 0 1-1.06 0L8.22 5.53a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L12 7.19l2.72-2.72a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734ZM12 15.75a.75.75 0 0 1 .75.75v5.75a.75.75 0 0 1-1.5 0V16.5a.75.75 0 0 1 .75-.75Z"
  /><path
    d="M12 8.5a.75.75 0 0 1-.75-.75v-6a.75.75 0 0 1 1.5 0v6a.75.75 0 0 1-.75.75ZM2.75 12a.75.75 0 0 1 .75-.75h1a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1-.75-.75Zm4 0a.75.75 0 0 1 .75-.75h1a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1-.75-.75Zm4 0a.75.75 0 0 1 .75-.75h1a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1-.75-.75Zm4 0a.75.75 0 0 1 .75-.75h1a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1-.75-.75Zm4 0a.75.75 0 0 1 .75-.75h1a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1-.75-.75Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'fold 24';
-->
