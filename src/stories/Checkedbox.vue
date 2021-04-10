<template>
<label>
    <input type="checkbox" tabindex="0" checked :class="`ccheckbox-type--${type}`"/>
    <span></span>
</label>
</template>

<script>
export default {
    name: 'CCheckbox',
    props: {
        type: {
            type: String,
            default: 'normal', // 'normal' or 'focus' or 'focustab' or 'disable'
        },
    },
    
};
</script>

<style scoped>
.ccheckbox-type--focus {
    background: #ffccd7;
    outline:5px solid hsl(98, 51%, 31%);
}

</style>