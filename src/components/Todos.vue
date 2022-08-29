<template>
    <div>
        <div v-bind:key="todo.id" v-for="todo in todos">
            <p>{{todo.title}}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Todos',
    components:{

    },
    props:["todos"]
}
</script>

<style scoped>

</style>