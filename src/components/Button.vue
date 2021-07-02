<template>
<button @click="onClick()" :style="{background: color}" class="btn">{{text}}</button>    
</template>

<script>
export default {
    name: 'Button',
    props: {
        text: String,
        color: String,
    },
    methods: {
        onClick() {
            this.$emit('btn-click');
        },
    },
}
</script>

<style scoped>
    .btn:hover {
        animation-name: btnHover;
        animation-duration: 200ms;
        animation-fill-mode: forwards;
    }

    @keyframes btnHover {
        100% {
            transform: scale(1.05);
        }
    }
</style>