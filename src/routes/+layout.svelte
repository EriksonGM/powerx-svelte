<script>

	import SideBar from '../layout/SideBar.svelte';
	import Footer from '../layout/Footer.svelte';
	import Notifications from '../layout/Notifications.svelte';
	import UserMenu from '../layout/UserMenu.svelte';
</script>

<!-- ========== Topbar Start ========== -->
<div class="navbar-custom">
	<div class="topbar container-fluid">
		<div class="d-flex align-items-center gap-lg-2 gap-1">

			<!-- Topbar Brand Logo -->
			<div class="logo-topbar">
				<!-- Logo light -->
				<a href="/" class="logo-light">
					<span class="logo-lg">
							<img src="/images/logo.png" alt="logo">
					</span>
					<span class="logo-sm">
							<img src="/images/logo.png" alt="small logo">
					</span>
				</a>

				<!-- Logo Dark -->
				<a href="/" class="logo-dark">
					<span class="logo-lg">
							<img src="/images/logo.png" alt="dark logo">
					</span>
					<span class="logo-sm">
							<img src="/images/logo.png" alt="small logo">
					</span>
				</a>
			</div>

			<!-- Sidebar Menu Toggle Button -->
			<button class="button-toggle-menu">
				<i class="ri-menu-2-fill"></i>
			</button>

		</div>

		<ul class="topbar-menu d-flex align-items-center gap-3">

			<!--<Search/>-->

			<Notifications />

			<li class="d-none d-sm-inline-block">
				<a class="nav-link" data-bs-toggle="offcanvas" href="#theme-settings-offcanvas">
					<i class="ri-settings-3-line fs-22"></i>
				</a>
			</li>

			<li class="d-none d-sm-inline-block">
				<div class="nav-link" id="light-dark-mode">
					<i class="ri-moon-line fs-22"></i>
				</div>
			</li>

			<li class="d-none d-md-inline-block">
				<a class="nav-link" href="{null}" data-toggle="fullscreen">
					<i class="ri-fullscreen-line fs-22"></i>
				</a>
			</li>

			<UserMenu />
		</ul>
	</div>
</div>
<!-- ========== Topbar End ========== -->

<!-- ========== Left Sidebar Start ========== -->
<div class="leftside-menu">
	<!-- Brand Logo Light -->
	<a href="/" class="logo logo-light">
                    <span class="logo-lg">
                        <img src="/images/logo.png" alt="logo">
                    </span>
		<span class="logo-sm">
                        <img src="/images/logo.png" alt="small logo">
                    </span>
	</a>

	<!-- Brand Logo Dark -->
	<a href="/" class="logo logo-dark">
                    <span class="logo-lg">
                        <img src="/images/logo.png" alt="dark logo">
                    </span>
		<span class="logo-sm">
                        <img src="/images/logo.png" alt="small logo">
                    </span>
	</a>
	<!-- Full Sidebar Menu Close Button -->
	<div class="button-close-fullsidebar">
		<i class="ri-close-fill align-middle"></i>
	</div>

	<!-- Sidebar -left -->
	<div class="h-100" id="leftside-menu-container" data-simplebar>
		<!-- Leftbar User -->
		<div class="leftbar-user">
			<a href="/">
				<img src="/images/user.png" alt="user" height="42" class="rounded-circle shadow-sm">
				<span class="leftbar-user-name mt-2">Michael Berndt</span>
			</a>
		</div>

		<SideBar />

		<div class="clearfix"></div>
	</div>
</div>
<!-- ========== Left Sidebar End ========== -->

<!-- ============================================================== -->
<!-- Start Page Content here -->
<!-- ============================================================== -->

<div class="content-page">
	<div class="content">

		<!-- Start Content-->
		<div class="container-fluid">

			<!-- start page title -->

			<!-- end page title -->
			<slot />
		</div> <!-- container -->

	</div> <!-- content -->

	<!-- Footer Start -->
	<Footer />
	<!-- end Footer -->

</div>