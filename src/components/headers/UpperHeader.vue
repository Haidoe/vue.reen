<template>
	<header>
		<div class="container">
			<ul class="info">
				<li> 
					<span id="message"></span> {{ email }} 
				</li>
				<li> 
					<span id="phone"></span> {{ contactNumber }}
				</li>
			</ul>

			<ul class="social-logo">
				<li v-for="media in socialMedia" v-bind:key="media"> 
					<span :id="media"></span> 
				</li>
			</ul>
		</div>
	</header>
</template>

<style lang="sass" scoped>
	@import "../../assets/scss/variables"

	header 
		box-sizing: border-box
		background: #F5F7FA
		height: 40px
		border-bottom: 3px solid #E6E9ED
		font-family: $main_font
		color: $main_color
		overflow: hidden

		div
			overflow: hidden 
			display: flex
			justify-content: space-between
			align-items: center

			@media only screen and (max-width: 400px)
				padding: 0 15px
			li 
				display: inline
				position: relative
				font-size: 12pt
				padding: 0 15px
				white-space: nowrap
			
				@media only screen and (max-width: 400px)
					padding: 0

			.info 
				@media only screen and (max-width: 800px)
					width: 100%
					display: flex
					justify-content: space-between
				li 
					margin-right: 15px
					box-sizing: border-box
					
					@media only screen and (max-width: 800px)
						margin: 0
					
					@media only screen and (max-width: 400px)
						font-size: 10pt
					span 
						display: inline-block
						background: url("../../assets/images/header/header-logo-sprite.png") no-repeat
						height: 12pt
						width: 20px

						@media only screen and (max-width: 400px)
							position: relative
							top: 2px
							width: 11px

			#message 
				background-position: 0 4px

			#phone 
				background-position: -120px 4px
			
			.social-logo 
				@media only screen and (max-width: 800px)
					display: none

				li span 
					background: url("../../assets/images/header/social-logo-sprite.png") no-repeat
					height: 15pt
					width: 26.67px
					display: inline-block
					cursor: pointer

				#fb 
					background-position: 10px 4px
				

				#google 
					background-position: -17px 4px
				

				#twitter 
					background-position: -49px 4px
				

				#pinterest 
					background-position: -79px 4px
				

				#behance 
					background-position: -109px 4px
				

				#basketball 
					background-position: -140px 5px
</style>

<script>
	export default {
		data: function () {
			return {
				email: "haidren.amalia@gmail.com",
				contactNumber: "+63 (956) 935 3234",
				socialMedia: [
					'fb',
					'google',
					'twitter',
					'pinterest',
					'behance',
					'basketball'
				]
			}
		}
	}
</script>