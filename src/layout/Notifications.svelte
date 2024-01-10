<script>
	import { IconBell, IconUserCircle } from '@tabler/icons-svelte';
</script>

<li class="dropdown notification-list">
	<a class="nav-link dropdown-toggle arrow-none" data-bs-toggle="dropdown" href="{null}" role="button"
		 aria-haspopup="false" aria-expanded="false">
		<!--<i class="ri-notification-3-line fs-22"></i>-->
		<IconBell/>
		<span class="noti-icon-badge"></span>
	</a>
	<div class="dropdown-menu dropdown-menu-end dropdown-menu-animated dropdown-lg py-0">
		<div class="p-2 border-top-0 border-start-0 border-end-0 border-dashed border">
			<div class="row align-items-center">
				<div class="col">
					<h6 class="m-0 fs-16 fw-semibold"> Notification</h6>
				</div>
				<div class="col-auto">
					<a href="{null}" class="text-dark text-decoration-underline">
						<small>Clear All</small>
					</a>
				</div>
			</div>
		</div>

		<div style="max-height: 300px;" data-simplebar>

			<h5 class="text-muted fs-12 fw-bold p-2 text-uppercase mb-0">Today</h5>
			<!-- item-->

			<a href="{null}" class="dropdown-item p-0 notify-item unread-noti card m-0 shadow-none">
				<div class="card-body">
					<div class="d-flex align-items-center">
						<div class="flex-shrink-0">
							<div class="notify-icon bg-primary">
								<i class="ri-message-3-line fs-18"></i>
							</div>
						</div>
						<div class="flex-grow-1 text-truncate ms-2">
							<h5 class="noti-item-title fw-semibold fs-14">Datacorp <small
								class="fw-normal text-muted float-end ms-1">1 min ago</small></h5>
							<small class="noti-item-subtitle text-muted">Caleb Flakelar commented on Admin</small>
						</div>
					</div>
				</div>
			</a>

			<!-- item-->
			<a href="{null}" class="dropdown-item p-0 notify-item read-noti card m-0 shadow-none">
				<div class="card-body">
					<div class="d-flex align-items-center">
						<div class="flex-shrink-0">
							<div class="notify-icon bg-info">
								<i class="ri-user-add-line fs-18"></i>
							</div>
						</div>
						<div class="flex-grow-1 text-truncate ms-2">
							<h5 class="noti-item-title fw-semibold fs-14">Admin <small
								class="fw-normal text-muted float-end ms-1">1 hr ago</small></h5>
							<small class="noti-item-subtitle text-muted">New user registered</small>
						</div>
					</div>
				</div>
			</a>

			<h5 class="text-muted fs-12 fw-bold p-2 mb-0 text-uppercase">Yesterday</h5>

			<!-- item-->
			<a href="{null}" class="dropdown-item p-0 notify-item read-noti card m-0 shadow-none">
				<div class="card-body">
					<div class="d-flex align-items-center">
						<div class="flex-shrink-0">
							<div class="notify-icon">
								<img src="assets/images/users/avatar-2.jpg" class="img-fluid rounded-circle" alt="" />
							</div>
						</div>
						<div class="flex-grow-1 text-truncate ms-2">
							<h5 class="noti-item-title fw-semibold fs-14">Cristina Pride <small
								class="fw-normal text-muted float-end ms-1">1 day ago</small></h5>
							<small class="noti-item-subtitle text-muted">Hi, How are you? What about our next meeting</small>
						</div>
					</div>
				</div>
			</a>

			<h5 class="text-muted fs-12 fw-bold p-2 mb-0 text-uppercase">31 Jan 2023</h5>

			<!-- item-->
			<a href="{null}" class="dropdown-item p-0 notify-item read-noti card m-0 shadow-none">
				<div class="card-body">
					<div class="d-flex align-items-center">
						<div class="flex-shrink-0">
							<div class="notify-icon bg-primary">
								<i class="ri-discuss-line fs-18"></i>
							</div>
						</div>
						<div class="flex-grow-1 text-truncate ms-2">
							<h5 class="noti-item-title fw-semibold fs-14">Datacorp</h5>
							<small class="noti-item-subtitle text-muted">Caleb Flakelar commented on Admin</small>
						</div>
					</div>
				</div>
			</a>

			<!-- item-->
			<a href="{null}" class="dropdown-item p-0 notify-item read-noti card m-0 shadow-none">
				<div class="card-body">
					<div class="d-flex align-items-center">
						<div class="flex-shrink-0">
							<div class="notify-icon">
								<IconUserCircle/>
							</div>
						</div>
						<div class="flex-grow-1 text-truncate ms-2">
							<h5 class="noti-item-title fw-semibold fs-14">Karen Robinson</h5>
							<small class="noti-item-subtitle text-muted">Wow ! this admin looks good and awesome design</small>
						</div>
					</div>
				</div>
			</a>
		</div>

		<!-- All-->
		<a href="{null}"
			 class="dropdown-item text-center text-primary text-decoration-underline fw-bold notify-item border-top border-light py-2">
			View All
		</a>

	</div>
</li>