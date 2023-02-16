<template>
    <div class="card-container">
        <div class="card-banner">
            <img src="src\assets\icon\Person.svg" alt="Icon">
            <h3>Account Sign In</h3>
            <span>Join our team workspace</span>
        </div>
        <div class="card-input">
            <div class="card-input--username">
                <label for="">Username</label>
                <input type="text" placeholder="John Doe">
            </div>
            <div class="card-input--password">
                <label for="">Password</label>
                <input type="text" placeholder="********">
                <span class="card-input--icon"></span>
            </div>
        </div>
        <div class="card-option">
            <div class="card-option--checkbox">
                <input type="checkbox" id="remember-checkbox">
                <label for="remember-checkbox">Remember me?</label>
            </div>
            <a href="/resetpassword">Forgot your password</a>
        </div>
        <a href='' class="card-cta">
            <span>Sign In</span>
            <span class="card-cta--icon"></span>
        </a>
    </div>
    <a href="/signin" class="account-option">
        <span>Not signed up ? Register you</span>
    </a>
</template>

<script>
import { defineProps } from 'vue'
import Banner from '../atomes/Banner.vue';



</script>

