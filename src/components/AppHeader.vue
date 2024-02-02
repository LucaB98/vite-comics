
<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                active: false,
            },
            {
                text: 'Comics',
                url: '#',
                active: true,
            },
            {
                text: 'Movies',
                url: '#',
                active: false,
            },
            {
                text: 'TV',
                url: '#',
                active: false,
            },
            {
                text: 'Games',
                url: '#',
                active: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                active: false,
            },
            {
                text: 'Videos',
                url: '#',
                active: false,
            },
            {
                text: 'Fans',
                url: '#',
                active: false,
            },
            {
                text: 'News',
                url: '#',
                active: false,
            },
            {
                text: 'Shop',
                url: '#',
                active: false,
            },
        ],
    })
};
</script>

<template>
    <header id="header">
        <div class="container">
            <section class="nav-header">
                <img src="../assets/img/dc-logo.png" alt="logo">
                <nav>
                    <ul class="flex">
                        <li v-for="(link, i) in links" :key="i"><a :href="link.url" :class="{ 'active': link.active }">{{
                            link.text }}</a></li>
                    </ul>
                </nav>
            </section>
        </div>
    </header>
</template>

<style>
#header {
    background-color: white;
}

.nav-header {
    display: flex;
    justify-content: space-between;
    align-items: center;

}

.nav-header img {
    margin: 15px;
    max-width: 100px;
}

ul li {
    list-style-type: none;
}

ul li a {
    padding: 10px;
    margin: 5px;

}

ul li a .active,
ul li a:hover {
    color: #0C7CEC;
}
</style>