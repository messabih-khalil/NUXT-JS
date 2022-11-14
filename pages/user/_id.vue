<template>
    <div>
        {{$route.params.id}}
    </div>
</template>

<script>
    export default{
        validate({params}){
            
            return !isNaN(params.id)
        }
    }
</script>