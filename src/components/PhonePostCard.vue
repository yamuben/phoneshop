<template>
    
    <div class="contai">
        <div class="containerPhone">
        <img src="../assets/phone.png" width="100%"/>
        <h3>i Phone 2</h3>
        <p>Storage: 128 Gb | COlor: Red</p>
    </div>
    </div>
</template>
<script>

export default {
    name:"PhonePostCard"
}
</script>

<style >
.contai{
    width:100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.containerPhone {
    width:250px;
    height:300px;
    background:rgb(200, 200, 200);
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 1rem;

}
</style>
