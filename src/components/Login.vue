<template>
    <div class="container mt-4">
        <div class="container">
            <h3 class="text-center">Авторизация</h3>
        </div>
        <form class="d-flex flex-column align-items-center g-3">
            <div class="col-md-6">
                <label for="validationServer03" class="form-label">Phone or email</label>
                <input type="text" class="form-control is-invalid" id="validationServer03"
                       aria-describedby="validationServer03Feedback" required>
                <div id="validationServer03Feedback" class="invalid-feedback">
                    Please provide a valid city.
                </div>
            </div>

            <div class="col-md-6">
                <label for="validationServer06" class="form-label">Password</label>
                <input type="password" class="form-control is-valid" id="validationServer06" required>
                <div class="valid-feedback">
                    Looks good!
                </div>
            </div>

            <div class="">
                <button class="btn btn-primary" type="submit">Submit form</button>
            </div>
        </form>
        <RouterLink to="/profile/registration" class="nav-link">Регистрация</RouterLink>
    </div>
</template>

<script>
export default {
    name: "Login"
}
</script>

<style scoped>

</style>
