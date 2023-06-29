<template>
    <li>
        {{ linkElement }}
    </li>
</template>
<script>
export default {
    props:[
        'linkElement'
    ]
    
}
</script>
<style lang="scss" scoped>
li{
    margin-bottom: 8px;
}
li:hover {
    color: #e2e8ef;
}
</style>