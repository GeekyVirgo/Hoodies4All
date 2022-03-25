<script>
    import "../styles.css";
</script>

<div id="wrapper">
    <!-- HEADER SECTION -->
    <header class="header">
        <div class="headerContainer">
            <ul class="headerMenu">
                <li class="headerItem">
                    <i class="iconz fa-solid fa-user fa-xl" />
                    <a href="/" class="headerLinks">Sign In</a>
                </li>

                <li class="headerItem">
                    <i class="iconz fa-solid fa-bag-shopping fa-xl" />
                    <a href="/" class="headerLinks">Shopping Bag</a>
                </li>
            </ul>
        </div>
    </header>

    <!-- NAV SECTION -->
    <nav class="navbar">
        <div class="navbarContainer">
            <a href="/" id="navLogo">Hoodies 4 All</a>

            <ul class="navbarMenu">
                <li class="navbarItem">
                    <a href="/men" class="navbarLinks">Men</a>
                </li>
                <li class="navbarItem">
                    <a href="/women" class="navbarLinks">Women</a>
                </li>
                <li class="navbarItem">
                    <a href="/boys" class="navbarLinks">Boys</a>
                </li>
                <li class="navbarItem">
                    <a href="/girls" class="navbarLinks">Girls</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- MAIN SECTION -->
    <main>
        <slot />
    </main>

    <!-- FOOTER -->
    <footer>Copyright &copy; 2022, JavaScript Junkies</footer>
</div>
