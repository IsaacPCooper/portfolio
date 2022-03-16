<script>
export default 
{
    name: 'stackCard',
    props :{
        techImg:{
            type: String,
        },
        techType:{
            type: String,
    },
}
}
</script>

<template>
<div class="rounded shadow-lg">
              <img :src="techImg"  height="250" width="250" class="bg-white shadow-md"/>
              <p class="text-center text-white text-xl my-2"> {{techType}} </p>
</div>
</template>