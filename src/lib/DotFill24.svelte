<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'dot fill 24';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  viewBox="0 0 24 24"><path d="M12 18a6 6 0 100-12 6 6 0 000 12z" /></svg
>
