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

<style scoped lang='scss'>

.bodyClass{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.body{
    max-width: 65%;
    margin: 7rem auto 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    img{
        height: 5rem;
        width: 5rem;
    }
}

.content{
    margin-top: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    
    h2{
        line-height: 1.7rem;
        font-family: Roboto Mono;
    }
}


</style>