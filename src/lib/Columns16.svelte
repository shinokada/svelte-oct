<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'columns 16';
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
    d="M2.75 0h2.5C6.216 0 7 .784 7 1.75v12.5A1.75 1.75 0 0 1 5.25 16h-2.5A1.75 1.75 0 0 1 1 14.25V1.75C1 .784 1.784 0 2.75 0Zm8 0h2.5C14.216 0 15 .784 15 1.75v12.5A1.75 1.75 0 0 1 13.25 16h-2.5A1.75 1.75 0 0 1 9 14.25V1.75C9 .784 9.784 0 10.75 0ZM2.5 1.75v12.5c0 .138.112.25.25.25h2.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25h-2.5a.25.25 0 0 0-.25.25Zm8 0v12.5c0 .138.112.25.25.25h2.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25h-2.5a.25.25 0 0 0-.25.25Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'columns 16';
-->
