<template>
    <div class="bodyClass">
        <div class="body">
            <img alt="Vue logo" src="../assets/logo.png">
            <div class="content">
                <h2>This is my first project (attempt)<br> and a remider
                    to new future projects using Vue.js !
                </h2>
            </div>

            <div class="cli">
                <h3>Install Vue.js</h3>
                <p>npm install -g @vue</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BodyComponent'
}
</script>

<style>


.bodyClass{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.body img{
    height: 5rem;
    width: 5rem;
}

.body{
    max-width: 65%;
    margin: 7rem auto 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.content{
    margin-top: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.content h2{
    line-height: 2rem;
}

.cli{
    margin-top: 1rem;
    max-width: 50%;
    padding: 1rem;

    font-family: monospace;
    background-color: #2e3646;
    color: #ddd;
    border-radius: 10px;
    min-width: 90%;
}

</style>