<template>
    <div>
  <div v-for="item in items" :key="item.id">
      {{ item.name }}
  </div>
    </div>
</template>
                                            
<script>
    export default {
        data() {
            return {
                key: value,

                items:[
                    {
                        id:1,
                        name:"bilal",
                    }
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>