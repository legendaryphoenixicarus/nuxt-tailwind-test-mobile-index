<template>
    <div class="tab-controls relative overflow-hidden">
        <nav class="tabs relative">
          <input type="radio" id="tab-1" name="tabs" data-target="panel-1" class="tab absolute appearance-none" checked />
          <label for="tab-1" class="relative z-10">Arbeitnehmer</label>

          <input type="radio" id="tab-2" name="tabs" data-target="panel-2" class="tab absolute appearance-none" />
          <label for="tab-2" class="relative z-10">Arbeitgeber</label>

          <input type="radio" id="tab-3" name="tabs" data-target="panel-3" class="tab absolute appearance-none" />
          <label for="tab-3" class="relative z-10">Temporärbüro</label>

          <div class="absolute transform transition-transform tab-slider"></div>
        </nav>
    </div>
</template>

<style>
  .tab-controls {
        width: 360px;
        height: 121px;
  }

  .tabs {
      top: 51.63px;
      left: 20px;
      width: 480px;
      height: 40px;
  }

  .tab {
      background: #FFFFFF 0% 0% no-repeat padding-box;
      border: 1px solid #CBD5E0;
  }

  .tab-slider {
      top: 0;
      width: 160px;
      height: 40px;
      background: #81E6D9 0% 0% no-repeat padding-box;
      border-radius: 12px 0px 0px 12px;
  }

  .tab:checked + label {
      color: #E6FFFA;
  }

  .tabs label {
      top: 12px;
      left: 32px;
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

  .horizTranslate-1 {
      left: 20px;
      transition: 0.5s;
  }

  .horizTranslate-2 {
      left: -60.25px;
      transition: 0.5s;
  }

  .horizTranslate-3 {
      left: -140.5px;
      transition: 0.5s;
  }

  #tab-1:checked ~ div {
    border-radius: 12px 0px 0px 12px;
    transition: 0.5s;
    --tw-translate-x: 0%;
  }

  #tab-2:checked ~ div {
    border-radius: 0;
    transition: 0.5s;
    --tw-translate-x: 100%;
  }

  #tab-3:checked ~ div {
    border-radius: 0px 12px 12px 0px;
    transition: 0.5s;
    --tw-translate-x: 200%;
  }
</style>