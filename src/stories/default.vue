<template>
    <section>
      <Checkbox></Checkbox>
      <Checkbox type="focus"></Checkbox>
      <Checkbox type="focustab" ></Checkbox>
      <input type="checkbox" disabled/>
    </section>
</template>

<script>
import Checkbox from './Checkbox';

export default {
    name: 'Default',
    components: { Checkbox },
};
</script>