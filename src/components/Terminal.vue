<template>
    <h1 class="title">Starting with Vue.js</h1>
    <div class="cli">
        <h3>Installing <strong>Vue.js</strong></h3>
        <p>npm install -g @vue</p>

        <h3>Creatting a <strong>new project</strong></h3>
        <p>vue create project-name</p>
    </div>

</template>

<script>
export default {
    name: 'TerminalWindow'
}
</script>

<style scoped lang='scss'>

.title{
    margin-top: 2rem;
    font-family: monospace;
}

div.cli{
    margin-top: 1rem;
    width: 70%;
    padding: 1rem;

    font-family: monospace;
    background-color: #2e3646;
    color: #ddd;
    border-radius: 10px;

    h3{
        font-weight: 500;
        font-size: 1rem;
        font-style: italic;
        margin: 12px 0 2px;
    }

    h3:first-child{
        margin-top: 0;
    }

    p{
        font-family: monospace;
        font-size: 1rem;
    }
}

</style>