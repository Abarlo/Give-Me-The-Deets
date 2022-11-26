<template>
    <div class="shop-item">
        <img src="https://quantumleapcapital.com/assets/image-cache/blogs/miracle-cure-232x300.bf33ebe1.jpg"></img>
        <h3>Miracle Cure</h3>
        <p>Cures all disease from now and in your future children.</p>
        <span class="price">$9,999.99</span>
    </div>
</template>

<script lang="ts">
import {Component, Prop, Vue} from "vue-property-decorator";

@Component
export default class ShopItem extends Vue {}
</script>

<style>
.price {
    color: green;
}
</style>
