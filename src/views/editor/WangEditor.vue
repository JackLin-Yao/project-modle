<template>
	<div>
		<WangEditor v-model="editorValue" placeholder="请输入..."></WangEditor>
		<!--		<WangEditor v-model="editorValue2" :disabled="true" placeholder=""></WangEditor>-->
	</div>
</template>

<script lang="ts" setup name="EditorWangEditor">
import WangEditor from '@/components/WangEditor/index.vue'
import { ref } from 'vue'

const editorValue = ref('<p>maku</p>')
// const editorValue2 = ref('<p>maku</p>')
</script>
