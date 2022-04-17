<template>
	<div class="" style="height: 100%">
		<!-- <v-row justify="center" align="center">
			<v-col cols="12" sm="8" md="6">
				<v-card>
					<v-card-title class="headline">
						Welcome to the Vuetify + Nuxt.js template
					</v-card-title>
					<v-card-text>
						<p>Thank you for developing with Vuetify and I look forward to bringing more exciting features in the future.</p>
						<div class="text-xs-right">
							<em><small>&mdash; John Leider</small></em>
						</div>
						<hr class="my-3">
						<a
							href="https://github.com/nuxt/nuxt.js"
							target="_blank"
							rel="noopener noreferrer"
						>
							Nuxt GitHub
						</a>
					</v-card-text>
					<v-card-actions>
						<v-spacer />
						<v-btn
							color="primary"
							nuxt
							to="/inspire"
						>
							Continue
						</v-btn>
					</v-card-actions>
				</v-card>
			</v-col>
		</v-row> -->

		<full-page :options="navigation" id="fullpage">
		<v-row id="intro-section" class="section page-section" justify="center" align="center" no-gutters>
			<v-col
				cols="12"
				class="content-wrapper d-flex"
			>
				<v-sheet
					height="100%"
					width="100%"
					color="transparent"
					style="position: relative"
				>
					<v-parallax src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" />
					<!-- <v-card
						width="50%"
						class="d-flex flex-column justify-center text-center"
					>
						<h1>{{ greeting }}</h1>
						<h1>
							Joseph Legere <br/>
							Software Developer
						</h1>
						<h2>and this is {{ journeyStart }}</h2>
						<v-list>
							<v-list-item
								v-for="({ title, to }, i) in navigation"
								:key="i"
								:to="to"
								router
								exact
							>
								<v-list-item-content>
									<v-list-item-title v-text="title" />
								</v-list-item-content>
							</v-list-item>
						</v-list>
					</v-card> -->
				</v-sheet>
			</v-col>
		</v-row>
		<v-row class="section page-section" justify="center" align="center" no-gutters>
			<v-col
				cols="12"
				class="content-wrapper d-flex"
			>
				<v-sheet
					height="100%"
					width="100%"
					color="transparent"
					class="d-flex"
				>
					<v-card
						width="50%"
						class="d-flex flex-column justify-center text-center"
					>
						<h1>Project Ongoing</h1>
						<h1>React</h1>
						<p>
							React is a Gift Giving App that shares the moment of gift giving between people, it includes features like Social Media and E-commerce. The app is built with React Native and is complemented with Back-End using GraphQL, Postgres and AWS EC2 and S3.
						</p>
					</v-card>
				</v-sheet>
			</v-col>
		</v-row>
		<v-row class="section page-section" justify="center" align="center" no-gutters>
			<v-col
				cols="12"
				class="content-wrapper d-flex"
			>
				<v-sheet
					height="100%"
					width="100%"
					color="transparent"
					class="d-flex"
				>
					<v-card
						width="50%"
						class="d-flex flex-column justify-center text-center"
					>
						<h1>Tendeal</h1>
						<h1>Mobile Application</h1>
						<p>
							Online E-commerce platform for B2B and B2C trading, supports English and Arabic.
						</p>
					</v-card>
				</v-sheet>
			</v-col>
		</v-row>
		<v-row class="section page-section" justify="center" align="center" no-gutters>
			<v-col
				cols="12"
				class="content-wrapper d-flex"
			>
				<v-sheet
					height="100%"
					width="100%"
					color="transparent"
					class="d-flex justify-center align-center text-center"
				>
					<h1>{{ farewell }}</h1>
				</v-sheet>
			</v-col>
		</v-row>
		</full-page>

		<v-row no-gutters>
			<v-col
				cols="12"
				class="pa-2"
			>
				<h5><i>Tech Expert</i></h5>
				<h1>{{ $route.params.uname }}</h1>
				<p>
					Hello, I’m a Full Stack Developer from Philippines. I'm currently a Master Student in Qatar University.
				</p>
			</v-col>
		</v-row>

		<v-row no-gutters>
			<v-col
				cols="6"
				md="4"
			>
				<v-card
					class="pa-4 transparent"
					flat
				>
					<!-- <v-img
						height="500"
						aspect-ratio="1.7"
						class="grey darken-4"
						src="/joseph_headshot.jpg" /> -->
				</v-card>
			</v-col>

			<v-col
				cols="6"
				md="4"
			>
				<v-card
					class="pa-2 text-justify"
					
					
				>
					<h4 class="pa-2 text-center">PROFFESIONAL PROFILE</h4>
						<p>
							I have been crafting beautiful websites, launching stunning brands and making clients happy for years.
						</p>
						<p>
							Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare sem sed quam tempus aliquet vitae eget dolor. Proin eu ultrices libero. Curabitur vulputate vestibulum elementum. Suspendisse id neque a nibh mollis blandit. Quisque varius eros ac purus dignissim.
						</p>
						<p>
							Praesent sit amet massa suscipit, auctor sapien non, egestas felis. Maecenas mattis aliquet est vitae dignissim. Suspendisse aliquam lacus mauris, id placerat felis faucibus quis. Suspendisse potenti. Etiam mattis, eros id porta iaculis, nisl purus dapibus leo, a lacinia tellus nunc sed nunc. faucibus quis. Suspendisse id porta iaculis.
						</p>
				</v-card>
			</v-col>

			<v-col
				cols="12"
				md="4"
			>
				<v-card
					class="pa-2 text-left"
					flat
					tile
				>
					<v-list-item>
						<v-list-item-content>
							<v-list-item-title>
								<strong>Name:</strong> Joseph Legere
							</v-list-item-title>
						</v-list-item-content>
					</v-list-item>
					<v-list-item>
						<v-list-item-content>
							<v-list-item-title>
								<strong>Date of Birth:</strong> April 2, 1993
							</v-list-item-title>
						</v-list-item-content>
					</v-list-item>
					<v-list-item>
						<v-list-item-content>
							<v-list-item-title>
								<strong>Email:</strong> josephrlegere@gmail.com
							</v-list-item-title>
						</v-list-item-content>
					</v-list-item>
				</v-card>
			</v-col>
		</v-row>
	</div>
</template>

<script>
	export default {
		data: () => ({
			greeting: "<ciao>",
			farewell: "</ciao>",
			journeyStart: "<MySory>",
			journeyEnd: "</MySory>",
			navigation: [
				{
					title: 'Profile',
					to: '#profile'
				},
				{
					title: 'Skills',
					to: '#skills'
				},
				{
					title: 'Contact',
					to: '#contact'
				}
			]
		})
	}
</script>

<style scoped>
	.page-section {
		height:						100vh;
	}
	.page-section .content-wrapper {
		height:						100%;
		position:					relative;
	}
	#intro-section .v-parallax {
		height:						100vh !important;
	}
</style>