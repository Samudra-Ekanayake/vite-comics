<script>

export default {

    data() {
        return {
            shopList: [
                {
                    img: "src/assets/buy-comics-digital-comics.png",
                    text: "DIGITAL COMICS"
                },

                {
                    img: "src/assets/buy-comics-merchandise.png",
                    text: "DC MERCHANDISE"

                },

                {
                    img: "src/assets/buy-comics-subscriptions.png",
                    text: "SUBSCRIPTION"

                },

                {
                    img: "src/assets/buy-comics-shop-locator.png",
                    text: "COMIC SHOP LOCATOR"

                },

                {
                    img: "src/assets/buy-dc-power-visa.svg",
                    text: "DC POWER VISA"

                },

            ],


        }
    },

}

</script>

<template>
    <div class="container-fluid bg-success">
        <div class="row">
            <div class="col-12">
                <ul>
                    <li v-for="element in shopList">
                        <img :src="element.img" alt="">
                        <span>{{element.text}}</span></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style></style>