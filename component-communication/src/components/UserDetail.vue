<template>
    <div class="component">
        <h3>User Details</h3>
        <p>Tuoi toi: {{ dmm }}</p>
        <button @click="dmm++">Doi tuoi</button>
    </div>
</template>

<script>
	export default {
		data: function () {
			return {
				dmm: 11
			}
		},
		// props: ['age'],
		method: {
			changeAge () {
				this.dmm = 12
			}
		}
	}
</script>