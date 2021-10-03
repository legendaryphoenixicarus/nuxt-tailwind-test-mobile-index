<template>
    <div class="tab-controls">
        <nav class="tabs">
            <button data-target="panel-1" id="tab-1" class="tab active absolute">
                <span class="absolute">Arbeitnehmer</span>
            </button>
            <button data-target="panel-2" id="tab-2" class="tab absolute">
                <span class="absolute">Arbeitgeber</span>
            </button>
            <button data-target="panel-3" id="tab-3" class="tab absolute">
                <span class="absolute">Temporärbüro</span>
            </button>
        </nav>
    </div>
</template>

<style>
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
    }

    #tab-1 {
        top: 711px;
        left: -60.25px;
        width: 160px;
        height: 40px;

        border-radius: 12px 0px 0px 12px;
        opacity: 1;
    }

    #tab-1 > span {
        top: 12px;
        left: 32px;
        width: 96px;
        height: 17px;

        text-align: center;
        font: normal normal bold 14px/17px 'Lato Medium';
        letter-spacing: 0.84px;
        opacity: 1;
    }

    #tab-2 {
        top: 711px;
        left: 100px;
        width: 160px;
        height: 40px;
        opacity: 1;
    }

    #tab-2 > span {
        top: 12px;
        left: 39.5px;
        width: 82px;
        height: 17px;

        text-align: center;
        font: normal normal bold 14px/17px 'Lato Medium';
        letter-spacing: 0.84px;
        opacity: 1;
    }

    #tab-3 {
        top: 711px;
        left: 260px;
        width: 160px;
        height: 40px;
        opacity: 1;
    }

    #tab-3 > span {
        top: 12px;
        left: 30.5px;
        width: 98px;
        height: 17px;

        text-align: center;
        font: normal normal bold 14px/17px 'Lato Medium';
        letter-spacing: 0.84px;
        opacity: 1;
    }
</style>