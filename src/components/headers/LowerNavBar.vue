<template>
	<nav>
		<div class="container">
			<div class="logo">
				<img src="../../assets/haidren-v2.svg">
			</div>

			<ul>
				<li v-for="menu in menuList" v-bind:key="menu"> {{ menu }} </li>
			</ul>

			<div class="nav-search">
				<span></span>
			</div>

			<div class="bars">
				<font-awesome-icon :icon="['fa', 'bars']" />
			</div>
		</div>
	</nav>
</template>

<style lang="sass" scoped>
	nav 
		box-sizing: border-box
		margin: 0
		padding: 0
		height: 110px
		width: 100%
		border-bottom: solid #E6E9ED 3px

		@media only screen and (max-width: 1310px)
			height: 90px

		@media only screen and (max-width: 800px)
			height: 70px

	.container 
		padding: 0 15px
		display: flex
		justify-content: space-between
		align-item: center

		.logo
			height: inherit
			display: flex
			align-items: center


		img 
			width: 225px
			height: auto
			cursor: pointer

			@media only screen and (max-width: 800px)
				width: 12em
				height: auto
		ul 
			height: inherit
			margin: 0 auto
			
			@media only screen and (max-width: 800px)
				display: none

		li 
			position: relative
			top: 45px
			display: inline
			font-size: 1.3em
			font-weight: bolder
			margin: 0 10px
			cursor: pointer
			white-space: nowrap

			@media only screen and (max-width: 1310px)
				font-size: 1em
				top: 35px
				margin: 0 7px
			
			&:hover
				color: #00BC9C
	

	.nav-search	
		float: right
		height: inherit
		text-align: right

		@media only screen and (max-width: 800px)
			display: none

		span 
			background: url('../../assets/images/header/header-logo-sprite.png') no-repeat
			background-position: -65px 4px
			height: 20px
			width: 20px
			display: inline-block
			position: relative
			top: 47px
			transform: scale(1.1)
			cursor: pointer

			@media only screen and (max-width: 1310px)
				top: 32px

	
	.bars
		display: flex
		align-items: center
		font-size: 30pt
		cursor: pointer
		
		svg
			display: none
			
			&:hover
				color: #00BC9C

			@media only screen and (max-width: 800px)
				display: initial		
</style>

<script>
	export default	{ 
		data: function () {
			return	{
				menuList: [
					'HOME',
					'ABOUT',
					'PROJECTS',
					'CONTACT'
				]
			}
		}
	}
</script>
