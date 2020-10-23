<template>
<div class="container">
    <app-quoted-grid :quotes="quotes"></app-quoted-grid>
</div>
</template>

<script>
import QuoteGrid from './components/QuoteGrid';

export default {
    data: function () {
        return {
            quotes: ["Just a quote!"],
            maxQuotes: 10,
        };
    },
    components: {
        appQuotedGrid: QuoteGrid
    }
};
</script>

<style></style>
