<template>
<div class="pane">
    <div class="info-pane">
        <i class="fas fa-cloud"></i>
        <label class="test-text">Tester</label>
    </div>
    <div class="open-weather">
        <button class="open-button">
            <i class="fas fa-chevron-down"></i>
        </button>
    </div>
</div>
</template>

<script>


export default {

}
</script>

<style scoped>
.pane {
    position: fixed;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.fas {
    height: 50%;
    width: 50%;
}
.info-pane {
    border: 1px solid gray;
    background: white;
    max-width: 500px;
    margin: 0 auto 0 auto;
    overflow: auto;
    min-height: 100px;
    padding: 30px;
    border-radius: 5px;
}
.open-weather {
    margin: 0 auto;
}
.open-button {
}
</style>