<template>
    <div class="module">
        <img src="../assets/images/logo.png" alt=""/>
        <h1 class="page1">{{msg}}</h1>
        <a href="{{url}}" class="green" target="_blank">{{url}}</a>
    </div>
</template>

<script>
    import Module from 'js/module'
    export default{
        data: function () {
            return {
                msg: Module.data(),
                url: Module.url
            }
        }
    }
</script>

<style lang="scss">
    html{
        .page1{
            color: #f00;
        }
    }
</style>