<nav>
    <h3>Fiber</h3>
    <div class="navigation-links">
        <p>Community</p>
        <p>Pricing</p>
        <p>Features</p>
    </div>
    <div class="user-credentials">
        <a href="none" class="sign-in-btn">Sign In</a>
        <a href="none" class="sign-up-btn">Sign Up</a>
    </div>
</nav>

<style>
    * {
        padding: 0;
        margin: 0;
        color: hsl(0,0,0);
        box-sizing: border-box;
    }

    a {
		text-decoration: none;
		color: black
	}

    nav {
        width: 100vw;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 2rem 8vw;
        background-color: hsl(56, 92%, 85%);
    }

    .navigation-links {
        display: flex;
        align-items: center;
    }

    .navigation-links > * {
        margin: 0 1rem;
    }

    .sign-in-btn {
        margin-right: 2rem;
        font-weight: 700;
        transition: all 250ms ease-in-out;
    }

    .sign-in-btn:hover {
        color: blueviolet;
    }

    .sign-up-btn {
        background-color: darkviolet;
        color: white;
        padding: 1rem 1.5rem;
        font-weight: 700;
        border-radius: 0.5rem;
        transition: all 250ms ease-in-out;
    }

    .sign-up-btn:hover {
        background-color: blueviolet;
    }

</style>