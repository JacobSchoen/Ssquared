<template>
    <div class="NavBar">
        <section class="NavBar__item">    
            <router-link 
                style="text-decoration: none; color: inherit;"
                to="/">S SQUARED PHOTOGRAPHY</router-link>
        </section>
        <section class="NavBar__item">
            <router-link
                style="text-decoration: none; color: inherit;"
                to="/">HOME</router-link>
        </section>
        <section class="NavBar__item">
            <router-link 
                style="text-decoration: none; color: inherit;"
                to="/about">ABOUT</router-link>
        </section>
        <section class="NavBar__item">
            <router-link 
                style="text-decoration: none; color: inherit;"
                to="/portfolio">PORTFOLIO</router-link>
        </section>
        <section class="NavBar__item">
            <router-link                 
                style="text-decoration: none; color: inherit;"
                to="/investment">INVESTMENT</router-link>
        </section>
        <section class="NavBar__item">
            <router-link 
                style="text-decoration: none; color: inherit;"
                to="/contact">CONTACT</router-link>
        </section>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.NavBar{
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
    height: inherit;
    padding: 0.5rem;
    background-color: var(--dark3);
}

.NavBar__item{
    padding: 0.5rem 1rem;
}
</style>