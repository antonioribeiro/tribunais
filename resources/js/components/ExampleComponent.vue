<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">{{ name }}</div>

                    <div class="card-body">I'm an example component.</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data: {
        name: 'Vuejs',
    },

    mounted() {
        console.log('Component mounted.')

        this.name = 'Javascript'
    },
}
</script>
