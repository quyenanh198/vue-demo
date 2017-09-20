<template>
	<div>
	<form class="RegForm">
		<input v-model="name" placeholder="name">
		<input v-model="pwd" placeholder="password>
		<button> Log in </button>

	</form>
	</div>
</template>


<script>
export default {
  name: 'RegForm',
  data: {
  	name: '',
  	pwd: ''
  }
}
</script>

<style>
</style>