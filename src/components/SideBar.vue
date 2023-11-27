<template>
    <nav>
        <q-header class="bg-grey-2 text-dark" bordered>
            <q-toolbar>
            <q-input borderless v-model="text" input-class="text-left" class="q-ml-md" label="Search shots..">
                <template v-slot:prepend>
                    <q-icon name="search" />
                </template>
            </q-input>
            <q-space></q-space>
            <q-separator vertical />
            <q-btn dense round flat icon="notifications" class="q-mx-lg">
                <g-badge floating transparent>
                    <span style="color: orange; margin-left: -4px;">4</span>
                </g-badge>
            </q-btn>
            
            <q-separator vertical/>
            <q-avatar class="q-ml-lg">
                <img src="https://cdn.quasar.dev/img/avatar.png" />
            </q-avatar>
            <q-btn color="dark" icon-right="fas fa-chevron-down" label="John Weekend" flat />
        </q-toolbar>
        </q-header>
        <q-drawer v-model="leftDrawerOpen" show-if-above bordered>
            <div class="q-mt-md q-ml-md">
                <q-btn dense flat round icon="lens" size="8.5px" color="red"></q-btn>
                <q-btn dense flat round icon="lens" size="8.5px" color="yellow"></q-btn>
                <q-btn dense flat round icon="lens" size="8.5px" color="green"></q-btn>
            </div>
            <q-list>
                <div class="text-center q-py-md">
                    <q-btn color="light-blue-8" icon="fas fa-cloud-upload-alt" label="Upload" class="q-px-lg"></q-btn>
                </div>
            </q-list>
        </q-drawer>
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