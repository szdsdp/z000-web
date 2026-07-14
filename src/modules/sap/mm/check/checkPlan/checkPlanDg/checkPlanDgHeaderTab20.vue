<template>
  <el-form class="app-el-form">
    <el-row>
      <szd-input-form-item-col label="物料凭证" :span="8" v-model="objData.header.mblnr" disabled />
      <szd-input-form-item-col label="物料凭证年度" :span="8" v-model="objData.header.mjahr" disabled />
      <szd-input-form-item-col label="SAP消息" :span="8" v-model="objData.header.sapMsg" disabled />
      <szd-input-form-item-col label="SAP消息ID" :span="8" v-model="objData.header.sapMessId" disabled />
    </el-row>
    <el-row>
      <szd-input-form-item-col label="冲销物料凭证" :span="8" v-model="objData.header.revMblnr" disabled />
      <szd-input-form-item-col label="冲销物料凭证年度" :span="8" v-model="objData.header.revMjahr" disabled />
      <szd-input-form-item-col label="冲销SAP消息" :span="8" v-model="objData.header.revSapMsg" disabled />
      <szd-input-form-item-col label="冲销SAP消息ID" :span="8" v-model="objData.header.revSapMessId" disabled />
    </el-row>
  </el-form>
</template>

<script>
  export default {
    props: ["objData", "SR"],
    data() {
      return {};
    },
    methods: {}
  };
</script>
