<template>
    <div class="segment-controls">
        <Tabs />
        <TabContent />
    </div>
</template>

<style>
    .segment-controls {
        width: 360px;
        height: 1055px;
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


                // activate new tabs and panel
                let classString = event.target.getAttribute('data-target');

                if (classString === null) {
                    event.target.parentElement.classList.add('active');
                    classString = event.target.parentElement.getAttribute('data-target');
                } else {
                    event.target.classList.add('active');
                }

                
                console.log(classString);
                console.log(document.getElementById('panels'));
                document.getElementById('panels').getElementsByClassName(classString)[0].classList.add("active");
            }

            for (let i = 0; i < tab.length; i++) {
                tab[i].addEventListener('click', onTabClick, false);
            }
        }
    }
</script>