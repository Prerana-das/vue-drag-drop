<template>
    <div :id="id"
    class="board"
    @dragover.prevent
    @drop.prevent="drop">
        </slot>
    </div>
</template>

<script>


export default {
 props:['id'],
 methods:{
     drop(){
     
     }
 }
}
</script>

<style>

</style>


