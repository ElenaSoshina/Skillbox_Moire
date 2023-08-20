<template>
    <!-- eslint-disable  -->
  <BaseFormField :title="title" :error="error">
    <textarea v-model="dataValue" class="form__input form__input--area" :placeholder="placeholder"></textarea>
  </BaseFormField>
</template>

<script>
import formFieldMixin from '@/mixing/formFieldMixin';

export default {
  mixins: [formFieldMixin],
};
</script>
