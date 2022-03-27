<script>
    // imports

    // variables
    let email;
    let password;

    // functions
    const fxnSubmit = () => {
        alert("Thank you for signing in");
    };
</script>

<h2>Sign In</h2>
<form on:submit|preventDefault={fxnSubmit}>
    <input type="text" placeholder="email" required />
    <input type="password" placeholder="password" required />
    <button>Sign In</button>
</form>

<style>
    h2 {
        color: black;
    }
</style>
