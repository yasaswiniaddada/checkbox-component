<template>
    <section>
      <CCheckbox></CCheckbox>
      <CCheckbox type="focus"></CCheckbox>
      <CCheckbox type="focustab"></CCheckbox>
      <input type="checkbox" disabled checked/>
    </section>
</template>

<script>
import CCheckbox from './Checkedbox';

export default {
    name: 'Checked',
    components: { CCheckbox },
};
</script>