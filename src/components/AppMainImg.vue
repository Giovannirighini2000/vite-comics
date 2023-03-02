
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
                    "thumb": "https://m.media-amazon.com/images/I/91ytkCTqkEL.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.posters.cz/image/750/poster/dc-comics-aquaman-i26317.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://upload.wikimedia.org/wikipedia/it/0/0e/Batgirl_1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://upload.wikimedia.org/wikipedia/it/1/19/Batman_3_variant.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://upload.wikimedia.org/wikipedia/it/thumb/8/8d/Batman_beyond_1-195x300.jpg/640px-Batman_beyond_1-195x300.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1DCMH025ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/51galZVEAtL.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1OMEG008ISBN_0.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/m/1/m1blin005isbn_0_etb5tnzfio9togjg.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/91Gxg6HHEHL.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://m.media-amazon.com/images/I/51ST+-IP+bL.jpg",
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
    <div class="back-card">
        <div class="container">
            <div class="place-button">
                <button class="button-series">
                    CURRENT SERIES
                </button>
            </div>

            <ul class="flex wrap">
                <AppMainCard v-for="(serie, i) in seriestv" :key="i" :series="serie.series" :thumb="serie.thumb" />
            </ul>
            <div class="flex button-load">
                <button class="button-load-style">
                    LOAD MORE
                </button>

            </div>
        </div>


    </div>
</template>



<style lang="scss">
.wrap {
    flex-wrap: wrap;
    gap: 24px;
}

.back-card {
    background-color: #1c1c1c;
}

.button-series {
    position: absolute;
    z-index: 1;
    margin-top: -20px;
    margin-left: -20px;
    padding: 15px 25px;
    background-color: #0282f9;
    color: white;
    border: none;
    font-size: 16px;
    font-weight: bold;
}

.place-button {
    padding-bottom: 50px;
}

.button-load {
    justify-content: center;
    padding: 40px 10px;
}

.button-load-style {
    padding: 8px 30px;
    background-color: #0282f9;
    color: white;
    border: none;
}
</style>