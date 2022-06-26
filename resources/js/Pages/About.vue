<template>
    <Layout>
        About {{ name }}
    </Layout>
</template>

<script>
import Layout from '../Layout'

export default {
    components: { Layout },
    props: {
        name: String
    }
}
</script>

<style>
</style>
