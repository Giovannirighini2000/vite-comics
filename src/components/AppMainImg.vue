
<script>
import AppMainCard from '../components/AppMainCard.vue'
export default {
    components: {

        AppMainCard,
    },
    data() {
        return {
            seriestv: [
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-01/shazam_ka2_1x1_0.jpg?w=1200",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }

            ]

        }
    },
}
</script>
<template>
    <div>
        <ul class="flex wrap container">
            <AppMainCard v-for="(serie, i) in seriestv" :key="i" :series="serie.series" :thumb="serie.thumb" />
        </ul>

    </div>
</template>



<style lang="scss">
.wrap {
    flex-wrap: wrap;
    gap: 24px;
}
</style>