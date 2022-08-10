<template>
	<section class="contact-us pt-10">
		<v-img
			class="pt-10"
			gradient="to bottom, rgb(166 199 156), rgb(227 227 227 / 86%)"
			src="https://img.freepik.com/free-photo/contact-us_36325-2135.jpg?size=626&ext=jpg"
		>
			<v-container>
				<h4 class="display-1 text-center mb-5">
					Get In Touch
				</h4>
				<v-divider />
				<br />
				<v-row>
					<v-col cols="12" lg="5">
						<v-form>
							<v-text-field label="Your Name" />
							<v-text-field label="Email" />
							<v-text-field label="Subject" />
							<v-textarea label="Message" />
							<v-btn large color="green" class="white--text"
								>Send Message</v-btn
							>
						</v-form>
					</v-col>
					<v-col cols="12" lg="5" offset="2">
						<v-card-text style="text-align: justify">
							If you want to know more about me. You can contact me. You can
							also give me your opinion about my portfolio site. My inbox is
							always open for you. I will try my best to reply to all of your
							messages. Thank you for visiting my portfolio site. <br /><br />
							Email: saikathossen3@gmail.com <br />
							Phone: +8801744510689 <br />
							Address: Dhaka, Bangladesh <br />
						</v-card-text>
						<v-card-actions>
							<a
								href="https://drive.google.com/file/d/1b9GbSKeK9i42XXrGWgaQtrn8IXrPyO9J/view?usp=sharing"
								class="text-decoration-none"
								target="_blank"
								><v-btn
									large
									elevation="5"
									color="pink"
									class="white--text  px-10 align-center my-1"
								>
									Download Resume
									<v-icon>mdi-download</v-icon>
								</v-btn>
							</a>
						</v-card-actions>
						<div class="map-section">
							<iframe
								className="map-style"
								src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3651.519929057742!2d90.42343431437455!3d23.764492984582493!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x5883c14dc505a27c!2zMjPCsDQ1JzUyLjIiTiA5MMKwMjUnMzIuMiJF!5e0!3m2!1sen!2sbd!4v1637606078456!5m2!1sen!2sbd"
								allowFullScreen=""
								loading="lazy"
								title="This is a unique title"
							></iframe>
						</div>
					</v-col>
				</v-row>
			</v-container>
		</v-img>
	</section>
</template>

<style scoped>
.map-section {
	flex-direction: flex-col;
	align-items: center;
	justify-content: center;
	margin-top: 15px;
	margin-bottom: 15px;
}
.map-style {
	height: 235px;
	width: 550px;
	border: 0;
}
</style>
