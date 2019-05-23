<div class="scroll-item">
    <slot></slot>
</div>

<style>
    .scroll-item {
        display: inline-block;
        position: relative;
        flex: none;
        margin-right: 6px;
        margin-left: 6px;
        margin-bottom: 6px;
    }
</style>

<svelte:options tag="sv-scrollable-item"/>
