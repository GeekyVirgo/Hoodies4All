<script>
    // imports

    // variables
    let username;
    let password;

    // functions
    const fxnSubmit = () => {
        alert("Thank you for signing in");
        username = "";
        password = "";
    };
</script>

<div class="formWrapper">
    <div class="loginLogo">
        <h1 class="loginLogoText">Hoodies 4 All</h1>
    </div>

    <div class="form">
        <form on:submit|preventDefault={fxnSubmit}>
            <div class="signIn">Sign In</div>
            <div class="username">
                <i class="fa-solid fa-user fa-xl" />
                <input
                    type="text"
                    placeholder="Username or Email"
                    required
                    bind:value={username}
                />
            </div>

            <div class="password">
                <i class="fa-solid fa-lock fa-xl" />
                <input
                    type="password"
                    placeholder="Password"
                    required
                    bind:value={password}
                />
            </div>

            <div class="options">
                <div class="rememberMe">
                    <input type="checkbox" id="rememberMe" />
                    <label for="rememberMe">Remember me?</label>
                </div>

                <div class="forgotPassword">
                    <a href="/">Forgot Password?</a>
                </div>
            </div>

            <button class="signInButton">Sign In</button>
        </form>
    </div>

    <div class="signUp">
        New to Hoodies 4 All? <a href="/">Create an account</a>
    </div>
</div>

<style>
    .formWrapper {
        padding: 20px 50px;
    }

    .loginLogoText {
        font-family: "Bilbo Swash Caps", sans-serif;
        font-size: 4rem;
        text-shadow: 3px 3px black;
        padding: 5px;
        color: white;
        font-weight: bolder;
        border-radius: 10px;
        background: #833ab4;
        background: -webkit-linear-gradient(
            to right,
            #fcb045,
            #fd1d1d,
            #833ab4
        );
        background: linear-gradient(to right, #fcb045, #fd1d1d, #833ab4);
    }

    .form {
        width: 100%;
        margin-top: 30px;
        margin-bottom: 30px;
    }

    .signIn {
        font-weight: 400;
        font-size: 35px;
        color: #fd1d1d;
    }

    .username,
    .password {
        display: block;
        border-radius: 10px;
        border: 1px solid rgba(0, 0, 0, 0.3);
        padding: 5px;
        margin: 10px 0;
    }

    div > i {
        color: #fcb045;
        font-size: 25px;
    }

    div > input {
        color: #fd1d1d;
        font-size: 20px;
        padding: 10px 20px 10px 5px;
        border: none;
        outline: none;
        background: none;
    }

    .options {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 5px 0;
        margin-bottom: 30px;
    }

    .signInButton {
        width: 100%;
        padding: 10px;
        border: none;
        font-size: 20px;
        border-radius: 10px;
        background-color: #833ab4;
        color: white;
        margin-bottom: 5px;
        cursor: pointer;
    }

    .forgotPassword a,
    .signUp a {
        text-decoration: none;
    }
</style>
