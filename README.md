# Svelte notes

## Paths
Absolute paths begin at the **src** level.

## File references

```
<script>
   import constants from "/src/localStorage/static/constants.json";
</script>
```
Referring later in HTML:
```
<a href={constants.URLtarget} target="_blank">
   {constants.URLText}
</a>
```

## Conditionals
```
{#if constants.DemoVersion}
  ...
{:else}
  ...
{/if}
```
