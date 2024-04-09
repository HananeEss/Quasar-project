<template>
    <h2>Your favorite techno</h2>

    <div>
        <q-input v-model="text" label="Write your favorite techno" :dense="dense" />
        <div class="q-pa-md q-gutter-sm">
            <q-btn color="white" text-color="black" label="ADD" />
        </div>
    </div>
    
</template>