<template>
<div class="cards">
    <div class="ms_contenitore_img position-relative">
        <div class="sfondo_uno position-absolute" v-if="!prima" v-on:mouseleave="prima = true"></div>
        <img :src="require(`../assets/images/${cardData.img}`)" alt="" v-on:mouseover="prima = false">
    </div>
    <div class="ms_contenitore_txt pt-4">
        <p>{{cardData.title}}</p>
    </div>
    <div class="ms_contenitore_numero ">
        <p>{{cardData.data}}</p>
    </div>
    <div class="ms_contenitore_sottotitolo ">
        <p>{{cardData.subtext}}</p>
    </div>
</div>
  

</template>

<script>
export default {
    name:"LeadingCard",
    props: {
        'cardData': Object
    },
    data () {
        return {
            prima: true,
        }
    }

}
</script>

<style scoped lang="scss">

    .ms_contenitore_img {

        .sfondo_uno {
            width: 100%;
            height: 100%;
            background-color: rgba(248, 96, 17,);
            background: linear-gradient(0deg, rgba(248,96,17,0.6175070711878502) 15%, rgba(248,96,17,0.14047625886292014) 67%);
            top: 0px;
            left: 0px;
        }

        img {
            width: 100%;
            height: 100%;

        }


    }

    .ms_contenitore_txt{
        border: none;
        border-bottom: 1px dashed rgba(128, 128, 128, 0.4);

        p {
        font-size: 24px;
        font-weight: 00;
        }
    }

    .ms_contenitore_numero p{
        font-size: 28px;
        font-weight: 600;
        padding-top: 10px;
    }

    .ms_contenitore_sottotitolo p{
        font-size: 10px;
        font-weight: 300;
        margin-top: -18px;
    }

</style>