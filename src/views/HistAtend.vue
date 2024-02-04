<script setup lang="ts">
import TabelaHist from '../components/TabelaHist.vue'
import Pagination from '../components/Pagination.vue'
import Search from '../components/Search.vue'
</script>

<template>
    <div class="container">
        <div class="flex justify-end my-3">
            <Search />
        </div>
        <div class="mb-3">
            <TabelaHist />
        </div>
        <div>
            <Pagination />
        </div>
    </div>
</template>