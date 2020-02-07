<template>
    <div class="component">
        <h3>Edit User</h3>
        <p>Tuoi cua toi: {{ age }}</p>
        <button>Thay doi</button>
    </div>
</template>

<script>
    export default {
        props: ['age']
    }
</script>