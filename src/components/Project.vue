<template>
	<section class="educaion py-6">
		<v-container>
			<h4 class="display-2 text-center mb-10">Projects</h4>
			<v-row>
				<v-col lg-4>
					<v-card class="mx-auto" max-width="344">
						<v-img
							src="https://i.ibb.co/brtTzQ6/Screenshot-2022-08-09-at-8-28-14-PM.png"
							height="140px"
						></v-img>

						<v-card-title>
							Moto Repair
						</v-card-title>

						<v-card-subtitle>
							<a
								href="https://github.com/saikat100/moto-repair-client"
								class="text-decoration-none"
								target="_blank"
							>
								<v-chip class="p-2" color="dark">
									<v-icon left size="20">mdi-github</v-icon>
									GitHub Link
								</v-chip></a
							>
						</v-card-subtitle>

						<v-card-actions>
							<v-btn color="orange lighten-2" text>
								Project Description
							</v-btn>

							<v-spacer></v-spacer>

							<v-btn icon @click="show = !show">
								<v-icon>{{
									show ? "mdi-chevron-up" : "mdi-chevron-down"
								}}</v-icon>
							</v-btn>
						</v-card-actions>

						<v-expand-transition>
							<div v-show="show">
								<v-divider></v-divider>

								<v-card-text>
									<p>
										This is a responsive MERN stack web application for
										motorcycle parts repair. In this site user can take our
										service, see his/her order list & reviews our site. If user
										want any services he/she must be authenticate with Gmail or
										Google. User can also have cancelled his order. But he/she
										can’t cancel his first order. If he/she want to cancel
										his/her order than need to order more than one services.
										There is a admin panel where admin can add more admins, add
										more services, update order condition of user. There is also
										a test admin. Where you can add service & change the order
										condition of any user. Test admin can not add more admin,
										delete core 6 services & our user’s reviews. But test admin
										can delete his added services.
									</p>
									<h4>
										Technology: React.js, Node.js, Express.js, MongoDB, Firebase
										Authentication, Integrating PayPal API, React-Bootstrap,
										Bootstrap, React Router Dom, HTML5, CSS3, JavaScript(ES6)
									</h4>
								</v-card-text>
							</div>
						</v-expand-transition>
					</v-card>
				</v-col>
				<v-col lg-4>
					<v-card class="mx-auto" max-width="344">
						<v-img
							src="https://i.ibb.co/fx5kD72/Refresh-Professional-Painting-Service.png"
							height="140px"
						></v-img>

						<v-card-title>
							Refresh Painting
						</v-card-title>

						<v-card-subtitle>
							<a
								href="https://github.com/saikat100/Refresh-Painting-Client"
								class="text-decoration-none"
								target="_blank"
							>
								<v-chip class="p-2" color="dark">
									<v-icon left size="20">mdi-github</v-icon>
									GitHub Link
								</v-chip></a
							>
						</v-card-subtitle>

						<v-card-actions>
							<v-btn color="orange lighten-2" text>
								Project Description
							</v-btn>

							<v-spacer></v-spacer>

							<v-btn icon @click="show = !show">
								<v-icon>{{
									show ? "mdi-chevron-up" : "mdi-chevron-down"
								}}</v-icon>
							</v-btn>
						</v-card-actions>

						<v-expand-transition>
							<div v-show="show">
								<v-divider></v-divider>

								<v-card-text>
									<p>
										User can take different services as their need, track status
										of their taken services, see all order Admin can view all
										order of services and change status of services. Admin also
										can add new admin. Users can review the specific product and
										give ratings. If user want any services he/she must be
										authenticate with Gmail or Google. User profile with orders.
										update password, name, other information. Admin product
										management, user management, order details. Service status
										manage updated like service in stock or out of stock.",
										technology
									</p>
									<h4>
										Technology: React.js, React-router, Express.js, Material UI,
										Bootstrap, MongoDB, Firebase Authentication
									</h4>
								</v-card-text>
							</div>
						</v-expand-transition>
					</v-card>
				</v-col>
				<v-col lg-4>
					<v-card class="mx-auto" max-width="344">
						<v-img
							src="https://i.ibb.co/pzkXGyh/purchase-Shop1.png"
							height="140px"
						></v-img>

						<v-card-title>
							Purchase Shop
						</v-card-title>

						<v-card-subtitle>
							<a
								href="https://github.com/saikat100/purchase-shop-clint"
								class="text-decoration-none"
								target="_blank"
							>
								<v-chip class="p-2" color="dark">
									<v-icon left size="20">mdi-github</v-icon>
									GitHub Link
								</v-chip></a
							>
						</v-card-subtitle>

						<v-card-actions>
							<v-btn color="orange lighten-2" text>
								Project Description
							</v-btn>

							<v-spacer></v-spacer>

							<v-btn icon @click="show = !show">
								<v-icon>{{
									show ? "mdi-chevron-up" : "mdi-chevron-down"
								}}</v-icon>
							</v-btn>
						</v-card-actions>

						<v-expand-transition>
							<div v-show="show">
								<v-divider></v-divider>

								<v-card-text>
									<p>
										It is a single page e-commerce website, where the user can
										see the details of any product and add it to the product
										cart. In the product details section, if the user wants, he
										can decrease the product. In the cart section, if the user
										wants, he can add multiple products and remove the product.
										This is a fully responsive site. Created this project using
										React.js I will add the payment getaway system in a few days
									</p>
									<h4>
										Technology: React.js, React-router, React-Hook, Bootstrap,
										Firebase Authentication
									</h4>
								</v-card-text>
							</div>
						</v-expand-transition>
					</v-card>
				</v-col>
				<v-col lg-4>
					<v-card class="mx-auto" max-width="344">
						<v-img
							src="https://i.ibb.co/nmcxpgJ/Screenshot-2022-08-09-at-7-19-21-PM.png"
							height="140px"
						></v-img>

						<v-card-title>
							Ylight Music
						</v-card-title>

						<v-card-subtitle>
							<a
								href="https://ylight-music.netlify.app/"
								class="text-decoration-none"
								target="_blank"
							>
								<v-chip class="p-2" color="dark">
									<v-icon left size="20">mdi-github</v-icon>
									GitHub Link
								</v-chip></a
							>
						</v-card-subtitle>

						<v-card-actions>
							<v-btn color="orange lighten-2" text>
								Project Description
							</v-btn>

							<v-spacer></v-spacer>

							<v-btn icon @click="show = !show">
								<v-icon>{{
									show ? "mdi-chevron-up" : "mdi-chevron-down"
								}}</v-icon>
							</v-btn>
						</v-card-actions>

						<v-expand-transition>
							<div v-show="show">
								<v-divider></v-divider>

								<v-card-text>
									<p>
										The Ylight app as an Open Source app. This SERVICE is
										provided by me at no cost and is intended for use as is.
										User can enjoy unlimited music without add.
									</p>
									<h4>
										Technology: React.js, Youtube API, React Router Dom, HTML5,
										CSS3, JavaScript(ES6)
									</h4>
								</v-card-text>
							</div>
						</v-expand-transition>
					</v-card>
				</v-col>
			</v-row>
		</v-container>
	</section>
</template>

<script>
export default {
	name: "Project",
	data: () => ({
		show: false,
	}),
};
</script>
