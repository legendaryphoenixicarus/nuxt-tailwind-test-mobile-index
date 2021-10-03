<template>
    <div class="tab-controls relative overflow-hidden">
        <nav class="tabs relative">
            <button data-target="panel-1" id="tab-1" class="tab active absolute">
                <span class="relative">Arbeitnehmer</span>
            </button>
            <button data-target="panel-2" id="tab-2" class="tab absolute">
                <span class="relative">Arbeitgeber</span>
            </button>
            <button data-target="panel-3" id="tab-3" class="tab absolute">
                <span class="relative">Temporärbüro</span>
            </button>
        </nav>
    </div>
</template>

<style>
    .tab-controls {
        /* top: 706px; */
        width: 360px;
        height: 90px;;
    }

    .tabs {
        top: 27px;
        left: 20px;
        width: 480px;
        height: 40px;
    }

    .tab.active {
        background: #81E6D9 0% 0% no-repeat padding-box;
        border: none;
    }

    .tab {
        background: #FFFFFF 0% 0% no-repeat padding-box;
        border: 1px solid #CBD5E0;
    }

    .tab.active > span {
        color: #E6FFFA;
    }

    .tab > span {
        color : #319795;
        font: normal normal 600 14px/17px 'Lato Light';
        letter-spacing: 0.84px;
        opacity: 1;
    }

    #tab-1 {
        width: 160px;
        height: 40px;
        border-radius: 12px 0px 0px 12px;
    }

    #tab-2 {
        left: 160px;
        width: 160px;
        height: 40px;
        opacity: 1;
    }

    #tab-3 {
        left: 320px;
        width: 160px;
        height: 40px;
        border-radius: 0px 12px 12px 0px;
        /* opacity: 1; */
    }
</style>