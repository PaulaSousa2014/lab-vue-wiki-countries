<template>
 <nav class="navbar is-info" role="navigation" aria-label="main navigation">
            <div class="container">
                <div class="navbar-brand">
                    <router-link class="navbar-item has-text-weight-semibold" :to="{name: 'countries'}">
                        LAB - WikiCountries
                    </router-link>
                </div>
            </div>
        </nav>
</template>

<script setup>
const navbar = (name)=>{
    return name
}


</script>

<style>

</style>