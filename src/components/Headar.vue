<template>
	<v-container class="mb-16">
		<v-app-bar
			app
			elevation="6"
			elevate-on-scroll
			height="80"
			scroll-target="#scrolling-techniques-7"
		>
			<v-topbar-logo
				><v-img class="logo" src="../assets/logo.png"></v-img
			></v-topbar-logo>
			<v-tabs
				center-active
				right
				background-color="transparent"
				active-class="active-tab"
			>
				<v-tab href="#home"
					><v-icon>mdi-home</v-icon><span class="mobileMenu">Home</span></v-tab
				>
				<v-tab href="#about"
					><v-icon>mdi-account</v-icon
					><span class="mobileMenu">About</span></v-tab
				>
				<v-tab href="#project"
					><v-icon>mdi-home</v-icon
					><span class="mobileMenu">Project</span></v-tab
				>
				<v-tab href="#contact"
					><v-icon>mdi-phone</v-icon
					><span class="mobileMenu">Contact</span></v-tab
				>
			</v-tabs>
		</v-app-bar>
	</v-container>
</template>

<style scoped>
@media only screen and (max-width: 768px) {
	.mobileMenu {
		display: none;
	}
}
</style>
