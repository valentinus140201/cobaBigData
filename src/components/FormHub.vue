<template>
    <div class="hub">
        <span contenteditable="true">Form</span>
        <span contenteditable="true">Hub</span>
    </div>
</template>

<style>
    html {
        height: 50%;
    }

    body {
        background: #ffffff;
        color: #ffffff;
        margin: 0;
        min-height: 100%;
        height: 100%;
        position: relative;
    }

    .hub {
        background: #1b1b1b;
        display: block;
        font-family: sans-serif;
        font-weight: bold;
        font-size: 1.3vw;
        position: absolute;
        transform: translate(20%, 0%);
        border-radius: 10px;
    }

    .hub span:nth-child(2) {
        background: #FF9900;
        color: #000000;
        border-radius: 0.3vw;
        padding: 0.4vw;
        display: inline-block;
    }
</style>
