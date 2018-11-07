<template>
    <div id="main_container" class="">
        <div id="nav_bar" class="">

        </div>
        <div id="content_wrapper" class="">

        </div>
    </div>    
</template>

<style scoped>
#main_container {
    position: absolute;
    top: 64px;
    left: 0;
    bottom: 0;
    right: 0;
    z-index: 1;
    -webkit-transition: all 0.2s ease;
    transition: all 0.2s ease;
}
#main_container #nav_bar {
    position: absolute;
    left: 0;
    bottom: 0;
    top: 0;
    background: #eeeeee;
    border-right: 2px solid transparent;

    width: 252px;
    font-family: 'Roboto', helvetica, arial, sans-serif;
    font-weight: 300;
}
</style>

