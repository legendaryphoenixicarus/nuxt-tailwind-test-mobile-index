<template>
    <div class="tab-controls">
        <nav class="tabs">
            <button data-target="panel-1" id="tab-1" class="tab active absolute">
                <span id="tab-label-1">Arbeitnehmer</span>
            </button>
            <button data-target="panel-2" id="tab-2" class="tab absolute">
                <span id="tab-label-2">Arbeitnehmer</span>
            </button>
            <button data-target="panel-3" id="tab-3" class="tab absolute">
                <span id="tab-label-3">Arbeitnehmer</span>
            </button>
        </nav>
    </div>
</template>

<style>
    #tab-1 {
        top: 711px;
        left: -60.25px;
        width: 160px;
        height: 40px;

        background: #81E6D9 0% 0% no-repeat padding-box;
        border-radius: 12px 0px 0px 12px;
        opacity: 1;
    }

    #tab-2 {
        top: 711px;
        left: 100px;
        width: 160px;
        height: 40px;

        background: #FFFFFF 0% 0% no-repeat padding-box;
        border: 1px solid #CBD5E0;
        opacity: 0;
    }

    #tab-3 {
        top: 723px;
        left: 260px;
        width: 98px;
        height: 17px;
        text-align: center;

        font: normal normal bold 14px/17px Lato;
        letter-spacing: 0.84px;
        color: #E6FFFA;
        opacity: 1;
    }
</style>