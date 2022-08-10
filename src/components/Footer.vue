<template>
	<v-footer dark padless>
		<v-card class="flex" flat tile>
			<v-card-title class="teal">
				<strong class="subheading"
					>Get connected with me on social networks!</strong
				>

				<v-spacer></v-spacer>

				<v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
					<v-icon size="24px">
						{{ icon }}
					</v-icon>
				</v-btn>
			</v-card-title>

			<v-card-text class="py-2 white--text text-center">
				<strong
					>Copyright ©{{ new Date().getFullYear() }} All rights reserved |
					Design & Develop by
					<a
						href="mailto:saikathossen3@gmail.com"
						target="_blank"
						class="green--text"
						>Saikat Hossain</a
					>
				</strong>
			</v-card-text>
		</v-card>
	</v-footer>
</template>

<script>
export default {
	data: () => ({
		icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
	}),
};
</script>
