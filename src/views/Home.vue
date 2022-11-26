<template>
    <div class="home">
        <h1>Totem</h1>
        <ShopItem></ShopItem>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import ShopItem from "@/components/ShopItem.vue"; // @ is an alias to /src

@Component({
    components: {
        ShopItem
    }
})
export default class Home extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
    margin: 40px 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}
</style>
