<template>
<label>
    <input type="checkbox" :indeterminate.prop="true" tabindex="0" :class="`checkbox-type--${type}`"/>
    <span></span>
</label>
</template>

<script>
export default {
    name: 'Checkbox',
    props: {
        type: {
            type: String,
            default: 'normal', // 'normal' or 'focus' or 'focustab' or 'disable'
        },
    },
};
</script>

<style scoped>

.checkbox-type--focus {
    background: #ffccd7;
    outline:5px solid hsl(103, 57%, 37%);
}

</style>