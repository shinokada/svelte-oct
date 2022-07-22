<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'horizontal rule 16';
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
  ><path
    fill-rule="evenodd"
    d="M0 7.75A.75.75 0 01.75 7h14.5a.75.75 0 010 1.5H.75A.75.75 0 010 7.75z"
  /></svg
>
