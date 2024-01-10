<script>
	import {
		IconHome,
		IconUsers,
		IconUser,
		IconFileDollar,
		IconFileLike,
		IconUrgent,
		IconNews
	} from '@tabler/icons-svelte';


</script>

<!--- Sidemenu -->
<ul class="side-nav">
	<li class="side-nav-item">
		<a href="/" class="side-nav-link">
			<IconHome/>
			<span> Inicio </span>
		</a>
	</li>

	<!--<li class="side-nav-title">Colaborador</li>-->

	<li class="side-nav-item">
		<a href="/salary-receipts" class="side-nav-link">
			<IconFileDollar/>
			<span> Recibos </span>
		</a>
	</li>

	<li class="side-nav-item">
		<a href="/service-declarations" class="side-nav-link">
			<IconFileLike/>
			<span> Declarações de Serviço </span>
		</a>
	</li>

	<li class="side-nav-item">
		<a href="/emergency-contacts" class="side-nav-link">
			<IconUrgent/>
			<span> Contactos de Emergencia</span>
		</a>
	</li>

	<li class="side-nav-item">
		<a href="/news" class="side-nav-link">
			<IconNews/>
			<span> Noticias </span>
		</a>
	</li>

	<li class="side-nav-item">
		<a href="/employees" class="side-nav-link">
			<IconUsers/>
			<span> Gestão de Colaboradores </span>
		</a>
	</li>



</ul>
<!--- End Sidemenu -->