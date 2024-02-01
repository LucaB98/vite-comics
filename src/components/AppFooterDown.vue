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
                        <li><a href="#">F</a></li>
                        <li><a href="#">T</a></li>
                        <li><a href="#">Y</a></li>
                        <li><a href="#">P</a></li>
                        <li><a href="#">M</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style>
#footer-down {
    background-color: #303030;
    height: 150px;
}

#footer-down .row {
    justify-content: space-between;
    align-items: center;
    height: 150px;
}

#footer-down .row .col {
    height: 100%;
}

.sing-up {
    display: flex;
    align-items: center;
}

.social {
    align-items: center;
}
</style>