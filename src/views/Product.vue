<template>
	<h1>Product</h1>
	my name is {{ this.$route.params.name }}<br />
	<button onclick="$router.push('/')">go to home</button><br/>
	<router-link to="/">Go to Home</router-link>
</template>
