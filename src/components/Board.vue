<template>
    <div :id="id"
    class="board"
    @dragover.prevent
    @drop.prevent="drop">
        </slot>
    </div>
</template>

<script>
</script>