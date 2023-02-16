<template>
    <div :class="{ display: !value1 }">
        <div class="card-container">
            <div class="card-banner">
                <span class="banner--img"></span>
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
            <a href='' class="card-cta" v-on:click.prevent="toggle">
                <span>Sign In</span>
                <span class="card-cta--icon"></span>
            </a>
        </div>
        <a href="#" class="account-option">
            <span>Not signed up ? Register you</span>
        </a>
    </div>
    <div :class="{ display: !value2 }">
        <div class="card-container">
            <div class="card-banner">
                <span class="banner--img"></span>
                <h3>Account Sign Up</h3>
                <span>Join our team workspace</span>
            </div>
            <div class="card-input">
                <div class="card-input--username">
                    <label for="">Username</label>
                    <input type="text" placeholder="John Doe">
                </div>
                <div class="card-input--username">
                    <label for="">E-mail</label>
                    <input type="text" placeholder="johnDoe@mail.com">
                </div>
                <div class="card-input--password">
                    <label for="">Password</label>
                    <input type="text" placeholder="********">
                    <span class="card-input--icon"></span>
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
            <a href='#' class="card-cta" v-on:click.prevent="toggle">
                <span>Sign Up</span>
                <span class="card-cta--icon"></span>
            </a>
        </div>
        <a href="" class="account-option">
            <span>Already an account ? Sign in</span>
        </a>
    </div>
</template>

<script>
export default {
    data() {
        
        return {
            value1: true,
            value2: false
        }
    },
    methods: {
        toggle(event) {
            event.preventDefault()
            this.value1 = !this.value1
            this.value2 = !this.value2
            console.log(this.value1)
            console.log(this.value2)
        }
    }
};
</script>

<style>
.display {
    display: none;
    flex-direction: column;
}
</style>

