<script>
	export let title = "";
	//export let path = [];
</script>

<svelte:head>
	<title>Digital Office - {title}</title>
</svelte:head>
<div class="row">
	<div class="col-12">
		<div class="page-title-box">
			<div class="page-title-right">
				<ol class="breadcrumb m-0">
					<li class="breadcrumb-item"><a href="{null}">Powerx</a></li>
					<li class="breadcrumb-item"><a href="{null}">Pages</a></li>
					<li class="breadcrumb-item active">Starter</li>
				</ol>
			</div>
			<h4 class="page-title">{title}</h4>
		</div>
	</div>
</div>