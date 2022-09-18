<template>
    <a-layout-footer style="text-align: center">
        Ant Design 2021
    </a-layout-footer>
</template>



<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'UserSpecifiedFooter',
        props: {
            msg: String,
        },
    });
</script>
