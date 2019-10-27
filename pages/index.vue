<template>
	<v-layout column justify-center align-center>
		<counter />
	</v-layout>
</template>

<script>
import Counter from "~/components/Counter.vue";

export default {
	components: {
		Counter
	}
};
</script>
