<template>
    <div class="q-pa-md">
        <div class="row q-col-glutter-md">
            <div class="col-4">
            <q-card class="my-card q-py-sm">
                <q-item>
                    <q-item-section avatar>
                    <q-avatar square>
                        <img src="https://cdn.quasar.dev/img/boy-avatar.png">
                    </q-avatar>
                    </q-item-section>
                    <q-item-section>
                        <q-item-label><strong>TimProject</strong></q-item-label>
                        <q-item-label>UI\UX Design</q-item-label>
                    </q-item-section>
                    <q-item-section>
                        <q-btn color="light-blue-8" label="Edit" class="q-px-md" />
                    </q-item-section>
                </q-item>

                <q-separator/>
                <q-item>
                <q-item-section>
                    <q-item-label class="text-center"><strong>69</strong></q-item-label>
                <q-item-section class="text-center" caption>Shots</q-item-section>
                </q-item-section>

                <q-item-section>
                    <q-item-label class="text-center"><strong>2341</strong></q-item-label>
                <q-item-section class="text-center" caption>Followers</q-item-section>
                </q-item-section>

                <q-item-section>
                    <q-item-label class="text-center"><strong>347</strong></q-item-label>
                <q-item-section class="text-center" caption>Following</q-item-section>
                </q-item-section>

                <q-item-section>
                    <q-item-label class="text-center"><strong>1290</strong></q-item-label>
                <q-item-section class="text-center" caption>Reposts</q-item-section>
                </q-item-section>
            </q-item>
            </q-card>
        </div>
        </div>
        
    </div>
</template>

<script>

export default {
    name: 'Home',
    data: () => ({
        value:0
    })
}

</script>