<template>
  <el-form class="app-el-form">
    <el-row>
      <szd-input-form-item-col label="SAP会计凭证编号" :span="6" v-model="objData.header.belnr" disabled />
      <szd-input-form-item-col label="SAP财年" :span="6" v-model="objData.header.gjahr" disabled />
      <szd-input-form-item-col label="SAP消息ID" :span="6" v-model="objData.header.sapMessId" disabled />
      <szd-input-form-item-col label="SAP消息" :span="6" v-model="objData.header.sapMsg" disabled />
    </el-row>
  </el-form>
</template>

<script>
  export default {
    props: ["objData", "SR", "wfOper"],
    data() {
      return {};
    },
    methods: {}
  };
</script>
