<script lang="ts">
  export let size = '16';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'dependabot 24';
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
    d="M8.75 11a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0v-3.5a.75.75 0 0 1 .75-.75Zm7.25.75a.75.75 0 0 0-1.5 0v3.5a.75.75 0 0 0 1.5 0v-3.5Z"
  /><path
    d="M9.813 1h2.437a.75.75 0 0 1 .75.75V5h6.75A2.25 2.25 0 0 1 22 7.25v5.25h1.25a.75.75 0 0 1 0 1.5H22v5.75A2.25 2.25 0 0 1 19.75 22H4.25A2.25 2.25 0 0 1 2 19.75V14H.75a.75.75 0 0 1 0-1.5H2V7.25A2.25 2.25 0 0 1 4.25 5h7.25V2.5H9.813A.75.75 0 0 1 9.812 1ZM3.5 7.25v12.5c0 .414.336.75.75.75h15.5a.75.75 0 0 0 .75-.75V7.25a.75.75 0 0 0-.75-.75H4.25a.75.75 0 0 0-.75.75Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = '16';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'dependabot 24';
-->
