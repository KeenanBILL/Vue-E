<template>
    <div>
        <form>
            <label for="">First Name<input type="text"></label>
            <label for="">Surname<input type="text"></label>
            <label for="">Contact Number<input type="text"></label>
            <label for="">Email Address<input type="text"></label>
            <button type="submit">Submit</button>
        </form>

    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
form input{
    border: solid 2px;
    display: flex;
    flex-direction: row;
    width: 60%;
    margin: auto;
    justify-content: space-around;
    border-radius: 20px;
}

label{
    justify-content: space-around;
    
}

button{
    width: 50%;
    border-radius: 20px;
}

</style>