<template>
    <nav class="wrapper-full top__navbar">
        <div class="wrapper">
            <div class="navbar__block-left">
                <nuxt-link to="/">
                    <i class="fa-solid fa-house pointer-hover"></i>
                </nuxt-link>
            </div>
            <div class="navbar__block-middle">
                <input type="text" placeholder="Search...">
            </div>
            <div class="navbar__block-right">
                <nuxt-link to="/">
                    <i class="fa-solid fa-envelope pointer-hover"></i>
                </nuxt-link>
                <nuxt-link to="/">
                    <i class="fa-solid fa-earth-europe pointer-hover"></i>
                </nuxt-link>
                <nuxt-link to="/">
                    <i class="fa-solid fa-square-plus"></i>
                </nuxt-link>
                <div class="profil-pic pointer-hover" style="background-image: url('/default.png');">
                    <div class="navbar__menu">
                        <nuxt-link to="/">
                            <i class="fa-solid fa-user"></i>
                            Profile
                        </nuxt-link>
                        <nuxt-link to="/">
                            <i class="fa-solid fa-gear"></i>
                            Settings
                        </nuxt-link>
                        <span>
                            <i class="fa-solid fa-right-from-bracket"></i>
                            Logout
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'topNavbar'
}
</script>