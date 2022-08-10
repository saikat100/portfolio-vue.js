<template>
	<v-app id="inspire">
		<Header />
		<TopBar />
		<About />
		<Education />
		<Project />
		<Contact />
		<Footer />
	</v-app>
</template>

<script>
import Header from "./components/Headar";
import TopBar from "./components/TopBar.vue";
import About from "./components/About.vue";
import Education from "./components/Education.vue";
import Project from "./components/Project.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
export default {
	name: "App",

	components: {
		Header,
		TopBar,
		About,
		Education,
		Project,
		Contact,
		Footer,
	},

	data: () => ({
		drawer: null,
	}),
};
</script>
<style>
.logo {
	height: 52px;
	width: 55px;
}
.v-tab.active-tab {
	color: #e91e63;
}

.v-tab.active-tab::before {
	background-color: #4caf50;
}
</style>
