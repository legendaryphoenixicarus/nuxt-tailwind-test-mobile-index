<template>
    <div id="panels" class="relative">
        <div class="panel-1 tab-content active">
            <span class="tab-panel-header absolute">Drei einfache Schritte zu deinem neuen Job</span>
            <div class="group-1 relative">
                <div class="image relative"></div>
                <span class="text text-1 absolute">1.</span>
                <span class="sub-text absolute">Erstellen dein Lebenslauf</span>
            </div>
            <div class="group-2 absolute">
                <span class="text text-2 absolute">2.</span>
                <span class="sub-text absolute">Erstellen dein Lebenslauf</span>
                <div class="image relative"></div>
            </div>
            <div class="group-3 absolute">
                <span class="text text-3 absolute">3.</span>
                <span class="sub-text absolute">Mit nur einem Klick bewerben</span>
                <div class="image relative"></div>
            </div>
        </div>
        <div class="panel-2 tab-content relative">
            <span class="tab-panel-header absolute">Drei einfache Schritte zu deinem neuen Mitarbeiter</span>
            <div class="group-1 relative">
                <div class="image relative"></div>
                <span class="text text-1 absolute">1.</span>
                <span class="sub-text absolute">Erstellen dein Unternehmensprofil</span>
            </div>
            <div class="group-2 absolute">
                <span class="text text-2 absolute">2.</span>
                <span class="sub-text absolute">Erstellen ein Jobinserat</span>
                <div class="image relative"></div>
            </div>
            <div class="group-3 absolute">
                <span class="text text-3 absolute">3.</span>
                <span class="sub-text absolute">Wähle deinen neuen Mitarbeiter aus</span>
                <div class="image relative"></div>
            </div>
        </div>
        <div class="panel-3 tab-content relative">
            <span class="tab-panel-header absolute">Drei einfache Schritte zur Vermittlung neuer Mitarbeiter</span>
            <div class="group-1 relative">
                <div class="image relative"></div>
                <span class="text text-1 absolute">1.</span>
                <span class="sub-text absolute">Erstellen dein Unternehmensprofil</span>
            </div>
            <div class="group-2 absolute">
                <span class="text text-2 absolute">2.</span>
                <span class="sub-text absolute">Erhalte Vermittlungs- angebot von Arbeitgeber</span>
                <div class="image relative"></div>
            </div>
            <div class="group-3 absolute">
                <span class="text text-3 absolute">3.</span>
                <span class="sub-text absolute">Vermittlung nach Provision oder Stundenlohn</span>
                <div class="image relative"></div>
            </div>
        </div>
        <div class="circle-1 z-20"></div>
        <div class="circle-3 z-0"></div>
    </div>
</template>

<style>
    #panels {
        /* top: 781px; */
        width: 360px;
        height: 956px;
        opacity: 1;
    }

    #panels > .circle-1 {
        position: absolute;
        top: 127px;
        left: -34px;
        width: 208px;
        height: 208px;
        border-radius: 50%;
        background: #F7FAFC 0% 0% no-repeat padding-box;
        opacity: 0.5;
    }

    #panels > .circle-3 {
        position: absolute;
        top: 629px;
        left: -54px;
        width: 304px;
        height: 303px;
        border-radius: 50%;
        background: #F7FAFC 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .tab-content {
        position: relative;
        display: none;
        width: 360px;
        height: 956px;
        opacity: 1;
    }

    .tab-content.active {
        display: block;
    }

    .tab-content .text {
        width: 106px;
        height: 156px;
        text-align: center;

        font: normal normal normal 130px/156px 'Lato Regular';
        letter-spacing: 0px;
        color: #718096;
        opacity: 1;
        z-index: 30;
    }

    .tab-content .image {
        z-index: 30;    
    }

    .tab-content .sub-text {
        /* width: 162px; */
        height: 19px;
        text-align: left;
        font: normal normal normal 16px/19px 'Lato Regular';
        letter-spacing: 0.47px;
        color: #718096;
        opacity: 1;
        z-index: 30;
    }

    .tab-panel-header {
        /* top: 781px; */
        left: 40px;
        width: 280px;
        height: 50px;
        text-align: center;
        font: normal normal 500 21px/25px 'Lato Medium';
        letter-spacing: 0px;
        color: #4A5568;
        opacity: 1;
    }

    /************************* Group 1 ***********************************/
    .group-1 {
        top: 70.06px;
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
        background: transparent url('/img/undraw_Profile_data_re_v81r.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .text-1 {
        top: 85.94px;
        left: 10px;
    }

    .group-1 > .sub-text {
        top: 176.94px;
        left: 137px;
    }

    .panel-1 > .group-1 > .sub-text {
        top: 195.94px;
        left: 137px;
    }

    /************************* Group 2 ***********************************/
    .group-2 {
        top: 307.06px;
        /* left: -63.47837829589844px; */
        width: 360px;
        height: 370px;
        background: transparent linear-gradient(134deg, #E6FFFA 0%, #EBF4FF 100%) 0% 0% no-repeat padding-box;
        opacity: 1;
        z-index: 10;
    }

    .panel-1 > .group-2 > .image {
        top: 182.03px;
        left: 112.26px;
        width: 181px;
        height: 127px;
        background: transparent url('/img/undraw_task_31wc.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-2 > .group-2 > .image {
        top: 131.01px;
        left: 58.52px;
        width: 259px;
        height: 179px;
        background: transparent url('/img/undraw_about_me_wa29.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-3 > .group-2 > .image {
        top: 170.18px;
        left: 102.32px;
        width: 218px;
        height: 148px;
        background: transparent url('/img/undraw_job_offers_kw5d.svg') 0% 0% no-repeat padding-box;
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

    .panel-3 > .group-2 > .sub-text {
        top: 118.94px;
        left: 162px;
    }

    /************************* Group 3 ***********************************/
    .group-3 {
        top: 629px;
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
        background: transparent url('/img/undraw_personal_file_222m.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-2 > .group-3 > .image {
        top: 173.46px;
        left: 5.6px;
        width: 240px;
        height: 197px;
        background: transparent url('/img/undraw_swipe_profiles1_i6mr.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .panel-3 > .group-3 > .image {
        top: 160px;
        left: 1px;
        width: 250px;
        height: 190px;
        background: transparent url('/img/undraw_business_deal_cpi9.svg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }

    .group-3 > .sub-text {
        top: 69px;
        left: 127px;
    }

    .panel-3 > .group-3 > .sub-text {
        top: 74px;
        left: 127px;
    }
</style>