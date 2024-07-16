<template>
    <header class="header bg-white w-full py-3 shadow-xl mb-20">
       <div class="container flex-center-between">
            <Logo/>
            <div class="flex-center-between flex gap-8">
                <ul class="list flex-center-between gap-8 font-normal">
                    <li class="list__item">
                        <RouterLink to="/menu">Bosh sahifa</RouterLink>
                    </li>
                    <li class="list__item">
                        <RouterLink to="/sevice">Xizmatlar</RouterLink>
                    </li>
                    <li class="list__item">
                        <RouterLink to="/portfolio">Portfolio</RouterLink>
                    </li>
                    <li class="list__item">
                        <RouterLink to="/team">Jamoa</RouterLink>
                    </li>
                    <li class="list__item">
                        <RouterLink to="/blog">Blog</RouterLink>
                    </li>
                    <li class="list__item">
                        <RouterLink to="/contacts">Kontaktlar</RouterLink>
                    </li>
                </ul>
                <a href="tel:+998909213711">
                    <Buttons text="+998 90 921 37 11"/>
                </a>
            </div>
       </div>
    </header>
</template>

<script setup>
import Logo from '../Common/Logo.vue'
import Buttons from '../Common/Buttons.vue'
</script>
