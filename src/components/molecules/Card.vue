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
                <input type="text">
            </div>
            <div class="card-input--password">
                <label for="">Password</label>
                <input type="text">
            </div>
        </div>
        <div class="card-option">
            <div class="card-option--checkbox">
                <input type="checkbox">
                <label for="">Remember me?</label>
            </div>
            <a href="">Forgot your password</a>
        </div>
        <div class="card-cta">
            <button>Sign In</button>
        </div>
    </div>
    <div>
        <a href=""></a>
    </div>
</template>

<script>
import { defineProps } from 'vue'
import Banner from '../atomes/Banner.vue';



</script>

