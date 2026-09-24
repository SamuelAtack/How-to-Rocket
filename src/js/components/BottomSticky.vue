<template>
    <div class="bottom-sticky">

        <div class="back-to-top">
            <a href="#contents" title="Jump back to contents">
                Contents
            </a>
        </div>
    </div>
</template>
<script>

export default {
    props: {
        unitSystem: {
            type: String
        }
    },
    data: () => ({
        
    }),
    methods: {
        test: () => {
            alert('test')
        }
    },
    computed: {
        units: () => {
            return 'US'
        }
    },
    created() {
        //
    }
}
</script>
