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
        <svg id="wave-up" class="absolute z-10" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 490" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(230, 255, 250, 1)" offset="0%"></stop><stop stop-color="rgba(235, 244, 255, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,0L80,24.5C160,49,320,98,480,98C640,98,800,49,960,40.8C1120,33,1280,65,1440,114.3C1600,163,1760,229,1920,269.5C2080,310,2240,327,2400,277.7C2560,229,2720,114,2880,73.5C3040,33,3200,65,3360,122.5C3520,180,3680,261,3840,261.3C4000,261,4160,180,4320,130.7C4480,82,4640,65,4800,98C4960,131,5120,212,5280,261.3C5440,310,5600,327,5760,302.2C5920,278,6080,212,6240,196C6400,180,6560,212,6720,261.3C6880,310,7040,376,7200,392C7360,408,7520,376,7680,375.7C7840,376,8000,408,8160,383.8C8320,359,8480,278,8640,228.7C8800,180,8960,163,9120,138.8C9280,114,9440,82,9600,122.5C9760,163,9920,278,10080,285.8C10240,294,10400,196,10560,155.2C10720,114,10880,131,11040,130.7C11200,131,11360,114,11440,106.2L11520,98L11520,490L11440,490C11360,490,11200,490,11040,490C10880,490,10720,490,10560,490C10400,490,10240,490,10080,490C9920,490,9760,490,9600,490C9440,490,9280,490,9120,490C8960,490,8800,490,8640,490C8480,490,8320,490,8160,490C8000,490,7840,490,7680,490C7520,490,7360,490,7200,490C7040,490,6880,490,6720,490C6560,490,6400,490,6240,490C6080,490,5920,490,5760,490C5600,490,5440,490,5280,490C5120,490,4960,490,4800,490C4640,490,4480,490,4320,490C4160,490,4000,490,3840,490C3680,490,3520,490,3360,490C3200,490,3040,490,2880,490C2720,490,2560,490,2400,490C2240,490,2080,490,1920,490C1760,490,1600,490,1440,490C1280,490,1120,490,960,490C800,490,640,490,480,490C320,490,160,490,80,490L0,490Z"></path></svg>
        <div class="group-2-back absolute z-10"></div>
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

    #wave-up {
        top: 307px;
    }

    #wave-down {
        top: 590px;
    }

    .group-2-back {
        top: 390.06px;
        /* left: -63.47837829589844px; */
        width: 360px;
        height: 177px;
        background: transparent linear-gradient(134deg, #E6FFFA 0%, #EBF4FF 100%) 0% 0% no-repeat padding-box;
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
        opacity: 1;
        z-index: 15;
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