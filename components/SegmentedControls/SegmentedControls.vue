<template>
    <div class="segment-controls">
        <Tabs />
        <TabContent />
    </div>
</template>

<style>
    .segment-controls {
        width: 360px;
        height: 1079px;
    }
</style>

<script>
    export default {
        mounted() {
            const tabs = document.querySelectorAll(".tabs");
            const tab = document.querySelectorAll(".tab");
            const panel = document.querySelectorAll(".tab-content");

            function onTabClick(event) {
                // deactivate existing active tabs and panel

                for (let i = 0; i < tab.length; i++) {
                    tab[i].classList.remove("active");
                }

                for (let i = 0; i < panel.length; i++) {
                    panel[i].classList.remove("active");
                }

                // get event target
                let target = event.target;

                // activate new tabs and panel
                let classString = event.target.getAttribute('data-target');

                if (classString === null) {
                    target = target.parentElement;

                    classString = target.getAttribute('data-target');
                }

                target.classList.add('active');
                
                console.log(classString);
                console.log(document.getElementById('panels'));

                document.getElementById('panels').getElementsByClassName(classString)[0].classList.add("active");

                // move tabs to the left or right.
                let targetId = target.getAttribute('id');
                // let shiftLeft = 20;

                tabs[0].classList.remove('horizTranslate-1', 'horizTranslate-2', 'horizTranslate-3');

                if (targetId === 'tab-1') {
                    tabs[0].classList.add('horizTranslate-1');
                    // shiftLeft = '20px';
                } else if (targetId === 'tab-2') {
                    tabs[0].classList.add('horizTranslate-2');
                    // shiftLeft = '-60.25px';
                } else if (targetId === 'tab-3') {
                    tabs[0].classList.add('horizTranslate-3');
                    // shiftLeft = '-140.5px';
                }

                // tabs[0].style.left = shiftLeft;
            }

            for (let i = 0; i < tab.length; i++) {
                tab[i].addEventListener('click', onTabClick, true);
            }
        }
    }
</script>