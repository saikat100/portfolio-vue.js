<template>
	<v-container class="mt-16 topber">
		<v-row class="align-center px-5">
			<v-col lg="6" cols="12" class="pa-6 font-weight-bold">
				<h2 class="display-3 myName">
					<span class="green--text">SAIKAT </span>
					<span class="pink--text"> HOSSAIN</span>
				</h2>
				<h4 class="font-weight-black">
					Spftware Engineer || Frontend Developer || Programmer
				</h4>
				<v-row class="mt-5 mb-16">
					<a
						href="https://www.linkedin.com/in/saikat-in/"
						class="text-decoration-none"
						target="_blank"
						><v-chip class="px-4 ma-3" color="info">
							<v-icon left size="20">mdi-linkedin</v-icon>
							Linkedin
						</v-chip></a
					>

					<a
						href="https://github.com/saikat100"
						class="text-decoration-none"
						target="_blank"
					>
						<v-chip class="px-4 ma-3" color="dark">
							<v-icon left size="20">mdi-github</v-icon>
							GitHub
						</v-chip></a
					>
					<a
						href="https://www.facebook.com/HashTagSaikat/"
						class="text-decoration-none"
						target="_blank"
						><v-chip class="px-4 ma-3" color="primary">
							<v-icon left size="20">mdi-facebook</v-icon>
							Facebook
						</v-chip></a
					>

					<a
						href="mailto:saikathossen3@gmail.com"
						class="text-decoration-none"
						target="_blank"
					>
						<v-chip class="px-4 ma-3 white--text" color="#01ff56">
							<v-icon left size="20">mdi-email</v-icon>
							Enail
						</v-chip></a
					>
				</v-row>
				<a
					href="https://www.linkedin.com/in/saikat-in/"
					class="text-decoration-none"
					target="_blank"
					><v-btn
						large
						elevation="5"
						color="green"
						class="white--text mt-10 px-5 py-5"
						>Hire Me</v-btn
					>
				</a>
				<a
					href="mailto:saikathossen3@gmail.com"
					class="text-decoration-none"
					target="_blank"
					><v-btn
						large
						elevation="5"
						color="pink"
						class="white--text mt-10 ml-10 px-5 py-5"
						>Contact
					</v-btn>
				</a>
			</v-col>
			<v-col lg="4" cols="12" class="px-5 mx-5">
				<v-img
					class="img-fluid image-size ml-15"
					src="https://i.ibb.co/6JMrntK/banner-img-61e36de3.jpg"
				></v-img>
			</v-col>
		</v-row>
	</v-container>
</template>

<style scoped>
.myName {
	animation: fadeIn 0.2s linear backwards 0.2s;
	font-weight: bold;
	text-shadow: -1px -1px 0 #17a2b8, 1px -1px 0 #17a2b8, -1px 1px 0 #17a2b8,
		1px 1px 0 #17a2b8;
	font-family: "Grenze Gotisch", cursive;
}
.image-size {
	box-shadow: 5px 5px 5px 5px #17a2b8;
	border-radius: 0 70px 0 70px;
	width: 230px;
	animation: fadeIn 0.2s linear backwards 0.4s;
}
@media only screen and (max-width: 768px) {
	.myName {
		font-weight: bold;
		font-size: 60px !important;
	}
	.image-size {
		width: 180px;
	}
}
@media only screen and (max-width: 600px) {
	.myName {
		font-weight: bold;
		font-size: 50px !important;
	}
	.image-size {
		width: 180px;
	}
}
@media only screen and (max-width: 281px) {
	.myName {
		font-weight: normal;
		font-size: 40px !important;
	}
	.image-size {
		width: 150px;
	}
}
</style>
