<template>
    <div class="">
        {{message.user.name}} : {{ message.message}}
    </div>

</template>

<script>
export default {
    props: ['message']
}
</script>
