<script>
	import NavLayout from '../NavLayout.svelte';
	import DocSidebar from './DocSidebar.svelte';
</script>

<NavLayout sidebar>
	<DocSidebar slot="sidebar" />

	<div class="flex" slot="content">
		<section class="xl:min-h-screen">
			<slot />
		</section>
	</div>
</NavLayout>
