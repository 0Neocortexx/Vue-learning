<script setup>

</script>

<template>
    <section> 
        <div>
            <form action="" method="post">
                <h2>LOGIN</h2>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
        
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                <button type="submit">Entrar</button><br><br>
                <a href="#">Forgot your password?</a><br>
                <p id="a">Already have a registration?</p>
            </form>
        </div>
    </section>
</template>

<style>
section {
    height: 480px;
    width: 450px;
    margin-top: 80px;
    box-shadow: 0 0 40px rgba(0, 0, 0, 0.1);
    padding: 10px;
    background-color: white;
    border-radius: 30px;
}

.box-login {
    text-align: center;
}

form {
    display: inline-block;
    text-align: left;
    padding: 20px;
    background-color: #fff;
}
form h2 {
    font-size: 20px;
}

label {
    display: block;
    margin-bottom: 10px;
}
input {
    width: 100%;
    padding: 8px;
    margin-bottom: 15px;
    box-sizing: border-box;
    border-radius: 5px;
}
button {
    background-color: #4caf50;
    color: #fff;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}


</style>