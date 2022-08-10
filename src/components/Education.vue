<template>
	<section class="experiance py-6">
		<v-img
			class="pa-10"
			gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
			src="https://i.ibb.co/ZL2k1j0/education-day-arrangement-table-with-copy-space.jpg"
		>
			<v-container>
				<h4 class="display-2 text-center">Education</h4>
				<v-timeline>
					<v-timeline-item
						v-for="(exper, index) in education"
						:key="index"
						:color="index % 2 === 0 ? 'pink' : 'green'"
					>
						<v-card class="rounded-xl">
							<v-card-title :color="index % 2 === 0 ? 'pink' : 'green'">
								{{ exper.title }}({{ exper.date }})
								<b
									><a class="green--text"
										>at {{ exper.institute }}
										<v-icon color="green">mdi-link</v-icon></a
									></b
								><br />
							</v-card-title>
						</v-card>
					</v-timeline-item>
				</v-timeline>
			</v-container>
		</v-img>
	</section>
</template>

<script>
export default {
	name: "Education",

	data: () => ({
		drawer: null,
		education: [
			{
				title: "M.Sc. (Eng.) in Software Engineering",
				institute: "Independent University, Dhaka",
				date: "2022-Present",
			},
			{
				title: "B.Sc.(Eng.) in Computer Science & Engineering",
				institute: "East West University Dhaka",
				date: "2016-2020",
			},
			{
				title: "H.S.C. in Science",
				institute: "Namuri Collage, Lalmonirhat",
				date: "2012-2014",
			},
			{
				title: "S.S.C. in Science",
				institute: "Namuri BL High School, Lalmonirhat",
				date: "2012",
			},
		],
	}),
};
</script>
