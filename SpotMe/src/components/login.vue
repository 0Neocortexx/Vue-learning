<script setup>
    import './../assets/login.css'

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