<script>
    import "../styles.css";
</script>

<div id="wrapper">
    <!-- HEADER SECTION -->
    <header class="header">
        <!-- sign in -->
        <!-- shopping bag -->
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
    <footer>
        <!-- footer -->
    </footer>
</div>
