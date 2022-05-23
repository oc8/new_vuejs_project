<template>
	<NavbarItem />
	<router-view />
</template>

<script>
import NavbarItem from './components/NavbarItem.vue';

export default {
	name: "App",
	components: {
    NavbarItem
},
};
</script>

<style>
* {
  border: 0;
  font-size: 100%;
  font-family: inherit;
}
*,
::before,
::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
.column {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.row {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.center {
  display: flex;
  justify-content: center;
  align-items: center;
}
.wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.stack {
  position: relative;
}
</style>
