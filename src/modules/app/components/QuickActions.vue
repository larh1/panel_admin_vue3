<template>
<li class="nav-item">
    <a class="nav-link" href="" @click.prevent="action">
        <i class="fa-regular fa-bell"></i>
    </a>
</li>
<li class="nav-item">
    <a class="nav-link" href="" @click.prevent="action">
        <i class="fa-solid fa-table-cells-large"></i>
    </a>
</li>
<li class="nav-item">
    <a class="nav-link" href="" @click.prevent="action">
        <i class="fa-regular fa-envelope"></i>
    </a>
</li>
</template>

<script>
export default
{
    name: "app-quick-actions",
    setup()
    {
        return {
            action: () => alert("Algo")
        }
    }
}
</script>

<style>

</style>
