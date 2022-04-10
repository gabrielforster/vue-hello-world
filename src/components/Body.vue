<template>
    <div class="bodyClass">
        <div class="body">
            <img alt="Vue logo" src="../assets/logo.png">
            <div class="content">
                <h2>
                    This is my first project using Vue. <br>
                    I'm coding it to learn Vue in practice, and
                    to have a reminder when I need some Vue thing.
                </h2>
            </div>

            <TerminalWindow />
            
        </div>
    </div>
</template>

<script>
import TerminalWindow from './Terminal.vue'

export default {
    name: 'BodyComponent',
    components: {
        TerminalWindow
    }

}
</script>

<style src='../assets/styles/App.scss' scoped lang='scss' />