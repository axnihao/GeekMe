<template>
	<div class="header clearfix">
		<img alt="GeekMelogo" src="../assets/logo.png">
		<div >{{ msg }}</div>
		<div id="main-header">
			<ul class="clearfix">
				<li><a href="">首页</a></li>
				<li><a href="">课程</a></li>
				<li><a href="">文章</a></li>
				<li><a href="">题集</a></li>
			</ul>
		</div>
		<div>
			<input type="text" value="search" />
		</div>
	</div>
</template>

<script>
	export default {
		name: 'header',
		props: {
			msg: String
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	h3 {
		margin: 40px 0 0;
	}

	ul {
		list-style-type: none;
		padding: 0;
	}

	li {
		display: inline-block;
		margin: 0 10px;
	}

	a {
		color: #42b983;
	}

	img {
		width: 50px;
		height: 50px;
	}
	
	.clearfix{
	    *zoom: 1;
	}
	.clearfix::after{
	    content: ".";
	    display: block;
	    clear: both;
	
	    height: 0;
	    visibility: hidden;
	}
</style>
