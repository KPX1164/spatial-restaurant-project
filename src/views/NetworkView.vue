<template>
    <div class="network-error">
        <h1>Uh-oh!</h1>
        <h3>
            It lools like you're experiencing some network issue, please take a breath and
            <a href="#" @click="router.go(-1)">click  here</a>
            to try again
        </h3>
        <p>Sorry, we can't get the data from the server.</p>
        <p>Please try again later</p>
    </div>
</template>

<script setup lang="ts">
import { useRouter } from 'vue-router';

const router = useRouter()

</script>