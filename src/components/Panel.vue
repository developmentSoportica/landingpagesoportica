<template>
<div class="div-panel" id="content">
      <h1 class="h1-panel">Panel administrativo</h1>
	<div class="div-father-panel">
		<router-link to="/cv">
			<img src="src/assets/images/icons/contacts.png" alt="">
			<h1>Hojas de vida</h1>
			<p>Hay muchas variaciones de los pasajes de Lorem Ipsum disponibles,
				 pero la mayoría sufrió alteraciones en alguna manera, ya sea porque se le agregó humor,</p>
		</router-link>
		<router-link to="/claimsPa">
			<img src="src/assets/images/icons/announcement.png" alt="">
			<h1>Quejas y reclamos</h1>
			<p>Hay muchas variaciones de los pasajes de Lorem Ipsum disponibles,
				 pero la mayoría sufrió alteraciones en alguna manera, ya sea porque se le agregó humor,</p>
		</router-link>
		<router-link to="/postulations">
			<img src="src/assets/images/icons/medal.png" alt="">
			<h1>Contactos</h1>
			<p>Hay muchas variaciones de los pasajes de Lorem Ipsum disponibles,
				 pero la mayoría sufrió alteraciones en alguna manera, ya sea porque se le agregó humor,</p>
		</router-link>
		<router-link to="/newpanel">
			<img src="src/assets/images/icons/newspaper.png" alt="">
			<h1>News letter</h1>
			<p>Hay muchas variaciones de los pasajes de Lorem Ipsum disponibles,
				 pero la mayoría sufrió alteraciones en alguna manera, ya sea porque se le agregó humor,</p>
		</router-link>
	</div>
<router-link to="/home" class="a-out-panel">
	<h4><i class="fa fa-power-off fa-2x" aria-hidden="true"></i></h4>
</router-link>
</div>
</template>
<script>
export default {
 	name: 'Panel',
	data () {
		return {
			tittle : 'Blog de soportica'
		}
	}
} 
</script>

