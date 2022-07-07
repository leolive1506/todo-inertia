<template>
    <Layout>
        About {{ name }}
    </Layout>
</template>

<script>
import Layout from '../Shared/Layout'

export default {
    components: { Layout },
    props: {
        name: String
    }
}
</script>

<style>
</style>
