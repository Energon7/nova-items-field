<template>
    <div>
        <span v-if="field.value">{{ JSON.parse(field.value).length }}</span>
        <span v-else>0</span>
    </div>
</template>

<script>
export default {
    props: ['resourceName', 'field'],
}
</script>
