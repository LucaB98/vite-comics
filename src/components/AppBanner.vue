<script>
export default {
    name: 'AppBanner',
};
</script>

<template>
    <div class="banner">
        <div class="container ">
            <ul class="list-banner">
                <li>
                    <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt="dg-comics"></a>
                    <h5>DIGITAL COMICS</h5>
                </li>
                <li>
                    <a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt="merchandise"></a>
                    <h5>DC MERCHANDISE</h5>
                </li>
                <li>
                    <a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator"></a>
                    <h5>SUBSCRIPTIONS</h5>
                </li>
                <li>
                    <a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions"></a>
                    <h5>COMIC SHOP LOCATOR</h5>
                </li>
                <li>
                    <a href="#"><img src="../assets/img/buy-dc-power-visa.svg" alt="visa"></a>
                    <h5>DC POWER VISA</h5>
                </li>
            </ul>

        </div>
    </div>
</template>

<style lang="scss" scoped>
.banner {
    background-color: #0C7CEC;
    color: white;
    height: 150px;
}

.container {
    height: 100%;
}

.list-banner {
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;

    li {

        display: flex;
        align-items: center;
    }
}


h5 {
    font-weight: 100;
    margin-left: 10px;
}

img {
    width: 50px;
    height: 100%;
}
</style>