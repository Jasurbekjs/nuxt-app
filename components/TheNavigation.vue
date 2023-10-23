<template>
    <nav class="nav">
        <h3>Nuxt App</h3>
        <div class="nuxt-links">
            <ul>
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/github">Github</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">About</NuxtLink>    
                </li>
            </ul>
        </div>
    </nav>
</template>

<style lang="css" scoped>

.nav {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 40px;
    padding: 0px 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: darkblue;
    color: #fff;

    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.nuxt-links ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

.nuxt-links ul li {
    margin-right: 0.5rem;
}
.nuxt-links ul li a {
    color: #fff;
    text-decoration: none;
}

.nuxt-links ul li a:hover {
    text-decoration: underline;
}
</style>