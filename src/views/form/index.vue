<script setup>
import { ref } from 'vue';

defineProps({
	msg: String,
});

const count = ref(0);
</script>

<template>
	<div class="manage">form</div>
</template>

<style lang="less" scoped>
.manage {
	width: 100%;
}
</style>
