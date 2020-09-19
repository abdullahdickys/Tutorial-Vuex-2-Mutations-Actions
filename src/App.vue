<template>
<<<<<<< HEAD
	<div id="app" class="container">
		<div class="row py-4">
			<agenda-input />
			<agenda-show />
		</div>
	</div>
</template>

<script>
	import AgendaInput from './components/AgendaInput.vue'
	import AgendaShow from './components/AgendaShow.vue'

	export default {
		name: 'app',
		components: {
			AgendaInput,
			AgendaShow
		}
	}
</script>
=======
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
>>>>>>> 0024d994b7487b724d40625a738df9156c785843
