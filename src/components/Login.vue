<template>
    <h1>Login</h1>
    <div class="wrapper">
        <form action="">

            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com" required>
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Password</label>
                <input type="password" class="form-control" id="exampleFormControlInput1" required>
            </div>
            <div>
                <button class="form-control" type="submit">login</button>
            </div>
        </form>
    </div>
</template>

<script>
    export default{
        name: 'LoginPage'
    }
</script>

<style scoped>
    .wrapper{
        width: 20rem;
        margin: auto;
        /* margin-top: 5rem; */
    }
    h1{
        margin: 4rem;
    }
</style>