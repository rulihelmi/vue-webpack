<template>
    <div>
        <h1>This is grate message</h1>
        <app-input></app-input>
    </div>
</template>

<script>
import input from './input.vue';
export default {
    components: {
        'app-input': input
    }
}
</script>