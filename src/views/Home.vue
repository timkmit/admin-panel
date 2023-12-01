<template>
    <div class="q-pa-md">
        <div class="row q-col-gutter-md">
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
            <q-separator />
            <q-item>
                <q-item-section>
                    <q-btn color="primary" icon="mail" label="Message" flat />
                </q-item-section>
                <q-item-section>
                    <q-btn-section>
                        <q-btn color="grey" label="Follow" />
                    </q-btn-section>
                </q-item-section>
            </q-item>
            </q-card>
        </div>
        <div class="col-4">
            <q-card class="my-card">
                <q-item>
                    <q-item-section>
                        <q-item-label caption>Give your support</q-item-label>
                    </q-item-section>
                </q-item>
                <q-separatop/>
                <q-item>
                    <q-item-section avatar>
                        <q-btn round color="blue-2" text-color="blue-8" icon="fas fa-bolt" />
                    </q-item-section>
                    <q-item-section>
                        <q-badge color="white text-black">Quantity:</q-badge>
                        <q-slider v-model="value" :min="-20" :max="20" :step="4" label="label-always" color="light-green" />
                    </q-item-section>
                </q-item>
                <q-separator />
                <q-item>
                    <q-item-section>
                    <q-btn color="primary" icon-right="fas fa-chevron-right" label="SUPPORT" flat />
                </q-item-section>
                </q-item>
            </q-card>
        </div>
        <div class="col4">
            <q-card class="my-card q-py-sm">
                <q-item>
                    <q-item-section>
                        <q-btn color="light-blue-8" icon="fab fa-facebook" label="Share with facebook" />
                    </q-item-section>
                    <q-item-section avatar>
                        <q-btn falt round color="grey-6" icon="fas fa-times" size="sm" /> 
                    </q-item-section>
                </q-item>
                <q-item>
                    <q-item-section>
                        <q-btn color="hrey-6" icon="fab fa-twitter" text-color="black" label="Share with twitter" outline />
                    </q-item-section>
                    <q-item-section avatar>
                        <q-btn flat round color="grey-6" icon="fas fa-items" size="sm" />
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