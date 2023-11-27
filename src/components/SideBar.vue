<template>
    <nav>
        <q-header class="bg-grey-2 text-dark" bordered>
            <q-input borderless v-model="text" input-class="text-left" class="q-ml-md" label="Search shots..">
                <template v-slot:prepend>
                    <q-icon name="search" />
                </template>
            </q-input>
            <q-space></q-space>
            <q-separator vertical />
            <q-btn dense round flat icon="far fa-bell" class="q=mx-lg">
                <g-badge color="green" floating transparent>4</g-badge>
            </q-btn>
        </q-header>
    </nav>
</template>
<script>
    export default {
        name: 'LayoutDefault',
        data: () => ({
                leftDrawerOpen: false,
                link: 'My page',
                text: ''
        })
    }
</script>
<style scoped>
.my-menu-link {
    border-left: 4px solid #2698D6
}
</style>