<template><!---->
    <div><!--mettre nom ou num (si inconnu)--></div>
    <div></div>
    <div>
        <h1>Clavier</h1>
        <div class="touchesclavier">
            <div>
                <button @click="">1</button>
                <button @click="">2</button>
                <button @click="">3</button>
            </div>

            <div>                
                <button @click="">4</button>
                <button @click="">5</button>
                <button @click="">6</button>
            </div>

            <div>                
                <button @click="">7</button>
                <button @click="">8</button>
                <button @click="">9</button>
            </div>

            <div>                
                <button @click="">#</button>
                <button @click="">0</button>
                <button @click="">*</button>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style>
button { 
    background-color: #b94244;
    border: black;
    border-radius:40px;
    padding: 20px;
    color: white;
    font-weight: bold;
}
</style>