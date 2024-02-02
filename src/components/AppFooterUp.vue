
<script>
export default {
    name: 'AppFooterUp',

};
</script>

<template>
    <footer id="footer-up">
        <div class="container">
            <div class="row flex">
                <div class="col">
                    <nav class="nav-footerup">
                        <section>
                            <h4>DC COMICS</h4>
                            <ul>
                                <li><a href="#">Characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul>
                        </section>

                        <section>
                            <h4>SHOP</h4>
                            <ul>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">Shop DC Collectibles</a></li>
                            </ul>
                        </section>

                        <section>
                            <h4>DC</h4>
                            <ul>
                                <li><a href="#">Terms Of Use</a></li>
                                <li><a href="#">Privacy policy (New)</a></li>
                                <li><a href="#">Ad Choices</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>
                                <li><a href="#">Subscriptions</a></li>
                                <li><a href="#">Talent Workshops</a></li>
                                <li><a href="#">CPSC Certificates</a></li>
                                <li><a href="#">Ratings</a></li>
                                <li><a href="#">Shop Help</a></li>
                                <li><a href="#">Contact Us</a></li>
                            </ul>
                        </section>

                        <section>
                            <h4>SITES</h4>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">DC Kids</a></li>
                                <li><a href="#">DC Universe</a></li>
                                <li><a href="#">DC Power Visa</a></li>
                            </ul>
                        </section>
                    </nav>
                </div>
                <div class="col">
                    <img class="logo" src="../assets/img/dc-logo-bg.png" alt="logo-bg">
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
#footer-up {
    height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

#footer-up .container {
    height: 100%;
}

.row {
    justify-content: space-between;
    height: 100%;
}

.col img {
    height: 100%;
}

.nav-footerup {
    height: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: flex-start;

    img {
        background-size: 100% 100%;
    }
}


section {
    margin: 30px 30px 0 0;
}

h4 {
    font-size: 1.10rem;
}


ul li {
    list-style-type: none;
    margin: 5px 0;

    a {
        color: #959595;
        font-size: 0.80rem;
        padding: 0;
        margin: 0;
    }
}
</style>