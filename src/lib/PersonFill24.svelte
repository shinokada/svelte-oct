<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'person fill 24';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  viewBox="0 0 24 24"
  ><path
    d="M12 2.5a5.25 5.25 0 00-2.519 9.857 9.005 9.005 0 00-6.477 8.37.75.75 0 00.727.773H20.27a.75.75 0 00.727-.772 9.005 9.005 0 00-6.477-8.37A5.25 5.25 0 0012 2.5z"
  /></svg
>
