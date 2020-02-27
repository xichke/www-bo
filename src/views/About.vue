<template>
    <div class="about">
        <h1>This is an about page</h1>
        <ul>
            <li v-for="item in users" :key="item.id">
                {{ item }}
            </li>
        </ul>
        <button v-on:click="test">test</button>
    </div>
</template>
<script>
export default {
    name: 'About',
    data() {
        return {
            users: []
        }
    },
    methods: {
        test: function() {
            const baseURI = 'https://jsonplaceholder.typicode.com/users'
            this.$http.get(baseURI)
                .then((result) => {
                    this.users = result.data
                })
        }
    }
}
</script>