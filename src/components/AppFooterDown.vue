<script>
export default {
    name: 'AppFooterDown',
};
</script>

<template>
    <footer id="footer-down">
        <div class="container">
            <div class="row flex">
                <div class="col sing-up">
                    <button class="btn">SING-UP NOW!</button>
                </div>
                <div class="col flex social">
                    <h2>FOLLOW US</h2>
                    <ul class="flex ">
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
#footer-down {
    background-color: #303030;
    height: 130px;

    .container {
        height: 100%;

        .row {
            justify-content: space-between;
            align-items: center;
            height: 100%;

            .col {
                height: 100%;
            }
        }
    }


}

ul {
    list-style-type: none;

    li {
        margin: 5px;
    }
}

a {
    padding: 5px;
}

.sing-up {
    display: flex;
    align-items: center;
}

.btn {
    padding: 10px;
    color: white;
    background-color: #303030;
    border: 2px solid #0C7CEC;
    font-size: 18px;
}

.social {
    align-items: center;

    h2 {
        color: #0C7CEC;
    }
}
</style>