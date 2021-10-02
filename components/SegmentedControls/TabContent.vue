<template>
    <div id="panels">
        <div class="panel-1 tab-content active">
            <span class="tab-panel-header absolute">Drei einfache Schritte zu deinem neuen Job</span>
            <div class="group-1 absolute">
                <div class="image absolute"></div>
                <p class="text-1 absolute">1.</p>
                <span class="sub-text absolute">Erstellen dein Lebenslauf</span>
            </div>
            <div class="group-2 absolute">

            </div>
        </div>
        <div class="panel-2 tab-content">
            <span class="tab-panel-header absolute">Drei einfache Schritte zu deinem neuen Mitarbeiter</span>
        </div>
        <div class="panel-3 tab-content">
            <span class="tab-panel-header absolute">Drei einfache Schritte zur Vermittlung neuer Mitarbeiter</span>
        </div>
    </div>
</template>

<style>
    .tab-content {
        display: none;
        /* top: 781px; */
        /* left: -63.47837829589844px; */
        width: 360px;
        height: 956px;
        opacity: 1;
    }

    .tab-content.active {
        display: block;
    }

    .tab-panel-header {
        top: 781px;
        left: 40px;
        width: 280px;
        height: 50px;
        text-align: center;
        font: normal normal normal 21px/25px Lato;
        letter-spacing: 0px;
        color: #4A5568;
        opacity: 1;
    }

    .group-1 {
        top: 851px;
        /* left: -34px; */
        width: 354px;
        height: 265px;
        opacity: 1;
    }

    .panel-1 > .group-1 > .image {
        /* top: 851px; */
        left: 100px;
        width: 220px;
        height: 145px;
        background: transparent url('./assets/img/undraw_Profile_data_re_v81r.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .text-1 {
        top: 85.94px;
        left: 10px;
        width: 106px;
        height: 156px;
        text-align: center;
        font: normal normal normal 130px/156px Lato;
        letter-spacing: 0px;
        color: #718096;
        opacity: 1;
    }

    .group-1 > .sub-text {
        top: 195.94px;
        left: 137px;
        width: 183px;
        height: 19px;
        text-align: left;
        font: normal normal normal 16px/19px Lato;
        letter-spacing: 0.47px;
        color: #718096;
        opacity: 1;
    }

    .group-2 {
        top: 1088px;
        /* left: -63.47837829589844px; */
        width: 520px;
        height: 370px;
        background: transparent linear-gradient(134deg, #E6FFFA 0%, #EBF4FF 100%) 0% 0% no-repeat padding-box;
        opacity: 1;
    }
</style>