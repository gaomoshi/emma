<script>
export default {
    data(){
        return {
            count:0
        }
    }
}
</script>

<template>
<button @click="count++">点我加1</button> <span>count is {{ count }}</span>

</template>