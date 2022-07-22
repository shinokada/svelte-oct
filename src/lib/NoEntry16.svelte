<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'no entry 16';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  viewBox="0 0 16 16"
  ><path d="M4.25 7.25a.75.75 0 000 1.5h7.5a.75.75 0 000-1.5h-7.5z" /><path
    fill-rule="evenodd"
    d="M16 8A8 8 0 110 8a8 8 0 0116 0zm-1.5 0a6.5 6.5 0 11-13 0 6.5 6.5 0 0113 0z"
  /></svg
>
