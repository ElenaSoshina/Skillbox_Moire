<template>
  <!-- eslint-disable  -->
  <BaseFormField :title="title" :error="error">
    <input v-model="dataValue" class="form__input" :type="type" :id="id" :placeholder="placeholder" :maxlength="maxlength"
      :v-mask="mask" />
  </BaseFormField>
</template>

<script>
import formFieldMixin from '@/mixing/formFieldMixin';

export default {
  props: ['type', 'id', 'maxlength', 'mask'],
  mixins: [formFieldMixin],
};
</script>
