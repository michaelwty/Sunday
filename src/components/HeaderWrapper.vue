<template>
    <div id="header_wrapper" class="old-leftpane with-board-views">
        <div class="header-nav">
        </div>
        <div class="header-content">

        </div>
    </div>    
</template>

<style scoped>
#header_wrapper {
    background: #eee;
    font-family: 'Roboto', helvetica, arial, sans-serif;
    font-weight: 300;
    position: relative;
    margin-bottom: 0px;
    height: 65px;
    font-size: 15px;
    z-index: 10;
    border-bottom: 1px solid #c4c4c4;
    left: 0;
    -webkit-transition: left 0.2s ease;
    transition: left 0.2s ease;
}
#header_wrapper .header-nav {
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    height: 65px;
    background: #eeeeee !important;
    width: 250px !important;
    border-right: 0;
}
#header_wrapper .header-content {
    display: block;
    padding-top: 10px;
    padding-left: 8px;
    border-bottom: 1px solid #e0e0e0;
    height: 65px;
    margin-left: 250px !important;
    background: #f7f7f7 !important;
}
</style>