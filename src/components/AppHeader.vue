<script>

export default {

    data() {
        return {

            navList: [
                "CHARACTER", "COMICS", "MOVIES",
                "TV", "GAMES", "COLLECTIBLES",
                "videos", "FANS", "NEWS", "SHOP"
            ]
        }
    },

}
</script>

<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 bg-success">
                <div class="row">
                    <div class="col-5 bg-primary ">
                        <div class="row">
                            <div class="col-8 bg-info d-flex align-items-center justify-content-center   ">
                                logo
                            </div>
                        </div>
                    </div>
                    <div class="col-7 bg-secondary p-2 d-flex justify-content-center align-items-center">
                        <div class="row d-flex  align-items-center ">
                            <ul class="st_headerList list-unstyled d-flex m-0">
                                <li  v-for="element in navList" class="m-1"><a href="">{{element}}</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style>
.st_headerList {
    font-size: 10px;
}

.st_headerList li a {
    color: black;
    text-decoration: none;
}
</style>