<template>
    <Layout title="Home">
        <div>
            <h1>This is the landing page! {{ foo }}</h1>    
        </div>   
    </Layout>  
</template>

<script>
import Layout from './Shared/Layout'

export default {
    props: ['foo'],
    components: {
        Layout,
    }
}
</script>
