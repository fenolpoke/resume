<script>
    export let href = '';
    export let text = '';
</script>

<div class="flex justify-center gap-1">
    <slot name="icon" />
    <a href="{href}">{text}</a>
</div>