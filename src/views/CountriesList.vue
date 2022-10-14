<template>

<router-link to="./CountriesDetails.vue"></router-link>

<div>
        

        <!-- container wrapper div -->
        <div class="container" style="height: calc(100vh - 52px);">
            <!-- columns wrapper div -->
            <div class="columns mt-0 " style="height: 100%;">
                <!-- Countries List (column) -->
                <div class="column is-4" style="overflow: auto">
                    <router-link class="media is-clickable" :to="{name: 'details', params: {code: country.alpha3Code}}">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/aw.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Aruba</strong>
                                </p>
                            </div>
                        </div>
                    </router-link>
                    <a class="media is-clickable" href="/AFG">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/af.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Afghanistan</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/AGO">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ao.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Angola</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/AIA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ai.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Anguilla</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ALA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ax.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Åland Islands</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ALA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/al.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Albania</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ALA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ad.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Andorra</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ARE">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ae.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>United Arab Emirates</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ARG">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/ar.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Argentina</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ARM">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/am.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Armenia</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ASM">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/as.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>American Samoa</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ATA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/aq.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Antarctica</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/FLK">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/fk.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Falkland Islands</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/FRA">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/fr.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>France</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                    <a class="media is-clickable" href="/ZWE">
                        <figure class="media-left">
                            <p class="image is-64x64">
                                <img src="https://flagpedia.net/data/flags/icon/72x54/zw.png" />
                            </p>
                        </figure>
                        <div class="media-content">
                            <div class="content">
                                <p>
                                    <strong>Zimbabwe</strong>
                                </p>
                            </div>
                        </div>
                    </a>
                </div>
                <!-- Country Details (column) -->
                <div class="column is-8">
                    <router-view />
                </div>
            </div>
        </div>
    </div>
   


</template>

<script setup>

</script>

<style>

</style>