<template>

       <section class="section">

<figure class="image is-128x128">
    <img src="https://flagpedia.net/data/flags/icon/72x54/fr.png">
</figure>
<div class="title">France</div>
<table class="table is-fullwidth">
    <tbody>
        <tr>
            <td>Capital</td>
            <td>Paris</td>
        </tr>
        <tr>
            <td>Area</td>
            <td>551695 km <sup>2</sup></td>
        </tr>
        <tr>
            <td>Borders</td>
            <td>
                <ul>
                    <li><a href="/AND">Andorra</a></li>
                    <li><a href="/BEL">Belgium</a></li>
                    <li><a href="/DEU">Germany</a></li>
                    <li><a href="/ITA">Italy</a></li>
                    <li><a href="/MCO">Monaco</a></li>
                    <li><a href="/ESP">Spain</a></li>
                    <li><a href="/CHE">Switzerland</a></li>
                </ul>
            </td>
        </tr>

    </tbody>
</table>
</section>
</template>


<script setup>
import {ref, onMounted} from 'vue'
import { useRoute} from 'vue-router'
import countries from '../assets/countries.json'

const route = useRoute();
const country = ref();

onMounted(() => {
    country.value = findCountry(route.params.code)
})

const findCountry = (code)=>{
  countries.find((country) => {
    return country.alpha3Code === code
  } )
}

</script>

<script>


</script>