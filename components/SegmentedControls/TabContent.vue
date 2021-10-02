<template>
    <div id="panels">
        <div class="panel-1 tab-content active">
            panel-1
        </div>
        <div class="panel-2 tab-content">
            Map here
        </div>
        <div class="panel-3 tab-content">
            other info
        </div>
    </div>
</template>

<style>
    .tab-content {
        display: none;
        top: 781px;
        left: -63.47837829589844px;
        width: 360px;
        height: 956px;
        position: absolute;
        opacity: 1;
    }

    .tab-content.active {
        display: block;
    }
</style>