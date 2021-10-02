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
                <p class="text-2 absolute">2.</p>
                <span class="sub-text absolute">Erstellen dein Lebenslauf</span>
                <div class="image absolute"></div>
            </div>
            <div class="group-3 absolute">
                <p class="text-3 absolute">3.</p>
                <span class="sub-text absolute">Mit nur einem Klick bewerben</span>
                <div class="image absolute"></div>
            </div>
        </div>
        <div class="panel-2 tab-content">
            <span class="tab-panel-header absolute">Drei einfache Schritte zu deinem neuen Mitarbeiter</span>
            <div class="group-1 absolute">
                <div class="image absolute"></div>
                <p class="text-1 absolute">1.</p>
                <span class="sub-text absolute">Erstellen dein Unternehmensprofil</span>
            </div>
            <div class="group-2 absolute">
                <p class="text-2 absolute">2.</p>
                <span class="sub-text absolute">Erstellen ein Jobinserat</span>
                <div class="image absolute"></div>
            </div>
            <div class="group-3 absolute">
                <p class="text-3 absolute">3.</p>
                <span class="sub-text absolute">Wähle deinen neuen Mitarbeiter aus</span>
                <div class="image absolute"></div>
            </div>
        </div>
        <div class="panel-3 tab-content">
            <span class="tab-panel-header absolute">Drei einfache Schritte zur Vermittlung neuer Mitarbeiter</span>
            <div class="group-1 absolute">
                <div class="image absolute"></div>
                <p class="text-1 absolute">1.</p>
                <span class="sub-text absolute">Erstellen dein Unternehmensprofil</span>
            </div>
            <div class="group-2 absolute">
                <p class="text-2 absolute">2.</p>
                <span class="sub-text absolute">Erhalte Vermittlungs- angebot von Arbeitgeber</span>
                <div class="image absolute"></div>
            </div>
            <div class="group-3 absolute">
                <p class="text-3 absolute">3.</p>
                <span class="sub-text absolute">Vermittlung nach Provision oder Stundenlohn</span>
                <div class="image absolute"></div>
            </div>
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

    .tab-content p {
        width: 106px;
        height: 156px;
        text-align: center;

        font: normal normal normal 130px/156px Lato;
        letter-spacing: 0px;
        color: #718096;
        opacity: 1;
    }

    .tab-content .sub-text {
        width: 183px;
        height: 19px;
        text-align: left;
        font: normal normal normal 16px/19px Lato;
        letter-spacing: 0.47px;
        color: #718096;
        opacity: 1;
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

    /************************* Group 1 ***********************************/
    .group-1 {
        top: 851px;
        /* left: -34px; */
        width: 354px;
        height: 265px;
        opacity: 1;
    }

    .group-1 > .image {
        /* top: 851px; */
        left: 100.44px;
        width: 220px;
        height: 145px;
        background: transparent url('./assets/img/undraw_Profile_data_re_v81r.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .text-1 {
        top: 85.94px;
        left: 10px;
    }

    .group-1 > .sub-text {
        top: 195.94px;
        left: 137px;
    }


    /************************* Group 2 ***********************************/
    .group-2 {
        top: 1088px;
        /* left: -63.47837829589844px; */
        width: 360px;
        height: 370px;
        background: transparent linear-gradient(134deg, #E6FFFA 0%, #EBF4FF 100%) 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-1 > .group-2 > .image {
        top: 182.03px;
        left: 112.26px;
        width: 181px;
        height: 127px;
        background: transparent url('./assets/img/undraw_task_31wc.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-2 > .group-2 > .image {
        top: 131.01px;
        left: 58.52px;
        width: 259px;
        height: 179px;
        background: transparent url('./assets/img/undraw_about_me_wa29.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-3 > .group-2 > .image {
        top: 170.18px;
        left: 102.32px;
        width: 218px;
        height: 148px;
        background: transparent url('./assets/img/undraw_job_offers_kw5d.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }


    .text-2 {
        top: 26.94px;
        left: 35px;
    }

    .group-2 > .sub-text {
        top: 138.94px;
        left: 162px;
    }

    /************************* Group 3 ***********************************/
    .group-3 {
        top: 1410px;
        left: 54px;
        width: 299px;
        height: 327px;
        opacity: 1;
    }

    .panel-1 > .group-3 > .image {
        top: 116.35px;
        left: 18px;
        width: 281px;
        height: 210px;
        background: transparent url('./assets/img/undraw_personal_file_222m.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-2 > .group-3 > .image {
        top: 173.46px;
        left: 5.6px;
        width: 240px;
        height: 197px;
        background: transparent url('./assets/img/undraw_swipe_profiles1_i6mr.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-3 > .group-3 > .image {
        top: 160px;
        left: 1px;
        width: 250px;
        height: 190px;
        background: transparent url('./assets/img/undraw_business_deal_cpi9.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .text-3 {
        /* top: 1410px; */
        /* left: 54px; */
    }

    .group-3 > .sub-text {
        top: 69px;
        left: 127px;
    }
</style>