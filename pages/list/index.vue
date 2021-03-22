<template>
<div>

<div class=window>
    <div class="title-bar">
        <div class="title-bar-text">メインコンテンツ</div>
    </div>
    <div class="window-body">
        <p>ようこそ</p>
    </div>
</div>

<v-card
@click="link"
>
    <v-card-title>title</v-card-title>
    <v-card-text>text</v-card-text>
</v-card>
</div>    
</template>
<script>
export default {
    methods: {
        link() {
            const param = 1
            
            this.$router.push({path: `detail/${param}`})
        }
    }

}
</script>
