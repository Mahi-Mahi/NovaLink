<template>
    <panel-item :field="field">
        <template slot="value">
            <p class="text-90"><a :href="field.value.url" target="_blank">{{ field.value.title }}</a></p>
        </template>
    </panel-item>
</template>

<script>
export default {
    props: ['resource', 'resourceName', 'resourceId', 'field'],
}
</script>
