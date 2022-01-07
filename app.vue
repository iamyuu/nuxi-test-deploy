<template>
	<div>
		<pre>{{ JSON.parse(data, null, 2) }}</pre>
		<NuxtWelcome />
	</div>
</template>

<script setup>
const { data } = useFetch("/api/time")
</script>
