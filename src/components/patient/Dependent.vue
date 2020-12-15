<template>
    <div class="main-wrapper">
        <layout-header3></layout-header3>
        <breadcrumb></breadcrumb>
        <!-- Page Content -->
		<div class="content">
			<div class="container-fluid">
				<div class="row">
					<!-- Profile Sidebar -->
					<div class="col-md-5 col-lg-4 col-xl-3 theiaStickySidebar">
						<sidebar1></sidebar1>
					</div>
					<!-- / Profile Sidebar -->
					<div class="col-md-7 col-lg-8 col-xl-9">
						<div class="card">
							<div class="card-body ">	<router-link to="/patient/add-dependent" class="btn book-btn add-btn" tabindex="0">Add Dependent</router-link>
								<!-- Dependent Tab -->
								<div class="mt-4">
									<div class="card card-table mb-0">
										<div class="card-body">
											<div class="table-responsive">
												<table class="table table-hover table-center mb-0">
													<thead>
														<tr>
															<th>Doctor</th>
															<th>Relationship</th>
															<th>gender</th>
															<th>Number</th>
															<th>Email</th>
															<th>Action</th>
														</tr>
													</thead>
													<tbody>
														<tr>
															<td>
																<h2 class="table-avatar">
																			<router-link to="/doctor/profile" class="avatar avatar-sm mr-2">
																				<img class="avatar-img rounded-circle" src="@/assets/img/doctors/doctor-thumb-01.jpg" alt="User Image">
																			</router-link>
																			<router-link to="/doctor/profile">Ruby Perrin <span>Dental</span></router-link>
																		</h2>
															</td>
															<td>Son</td>
															<td>Male</td>
															<td>9854367346</td>
															<td>abc@gmail.com</td>
															<td>
																<div class="table-action">
																	<router-link to="/patient/edit-dependent" class="btn btn-sm bg-info-light">	<i class="fas fa-edit"></i> Edit</router-link>
																</div>
															</td>
														</tr>
														<tr>
															<td>
																<h2 class="table-avatar">
																			<router-link to="/doctor/profile" class="avatar avatar-sm mr-2">
																				<img class="avatar-img rounded-circle" src="@/assets/img/doctors/doctor-thumb-01.jpg" alt="User Image">
																			</router-link>
																			<router-link to="/doctor/profile">Ruby Perrin <span>Dental</span></router-link>
																		</h2>
															</td>
															<td>Daughter</td>
															<td>Female</td>
															<td>9854367346</td>
															<td>abc@gmail.com</td>
															<td>
																<div class="table-action">
																	<router-link to="/patient/edit-dependent" class="btn btn-sm bg-info-light">	<i class="fas fa-edit"></i> Edit</router-link>
																</div>
															</td>
														</tr>
														<tr>
															<td>
																<h2 class="table-avatar">
																			<router-link to="/doctor/profile" class="avatar avatar-sm mr-2">
																				<img class="avatar-img rounded-circle" src="@/assets/img/doctors/doctor-thumb-01.jpg" alt="User Image">
																			</router-link>
																			<router-link to="/doctor/profile">Ruby Perrin <span>Dental</span></router-link>
																		</h2>
															</td>
															<td>Father</td>
															<td>Male</td>
															<td>9854367346</td>
															<td>abc@gmail.com</td>
															<td>
																<div class="table-action">
																	<router-link to="/patient/edit-dependent" class="btn btn-sm bg-info-light">	<i class="fas fa-edit"></i> Edit</router-link>
																</div>
															</td>
														</tr>
														<tr>
															<td>
																<h2 class="table-avatar">
																			<router-link to="/doctor/profile" class="avatar avatar-sm mr-2">
																				<img class="avatar-img rounded-circle" src="@/assets/img/doctors/doctor-thumb-01.jpg" alt="User Image">
																			</router-link>
																			<router-link to="/doctor/profile">Ruby Perrin <span>Dental</span></router-link>
																		</h2>
															</td>
															<td>Mother</td>
															<td>Male</td>
															<td>9854367346</td>
															<td>abc@gmail.com</td>
															<td>
																<div class="table-action">
																	<router-link to="/patient/edit-dependent" class="btn btn-sm bg-info-light">	<i class="fas fa-edit"></i> Edit</router-link>
																</div>
															</td>
														</tr>
													</tbody>
												</table>
											</div>
										</div>
									</div>
								</div>
								<!-- /Dependent Tab -->
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /Page Content -->
        <layout-footer></layout-footer>
    </div>
</template>