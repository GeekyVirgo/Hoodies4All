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
                    <a href="/login" class="headerLinks">Sign In</a>
                </li>

                <li class="headerItem">
                    <i class="iconz fa-solid fa-bag-shopping fa-xl" />
                    <a href="/cart" class="headerLinks">Shopping Bag</a>
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
    <footer>
        <div class="footerContainer">
            <div class="footerContent">
                <h3 class="footerHeader">Contact Us</h3>
                <ul class="footerMenu">
                    <li class="footerLinks"><a href="/">Call</a></li>
                    <li class="footerLinks"><a href="/">Text</a></li>
                    <li class="footerLinks"><a href="/">Email</a></li>
                    <li class="footerLinks"><a href="/">Chat</a></li>
                </ul>
            </div>

            <div class="footerContent">
                <h3 class="footerHeader">Customer Service</h3>
                <ul class="footerMenu">
                    <li class="footerLinks">
                        <a href="/">Returns & Exchanges</a>
                    </li>
                    <li class="footerLinks"><a href="/">Order Status</a></li>
                    <li class="footerLinks"><a href="/">Return Policy</a></li>
                    <li class="footerLinks"><a href="/">FAQ</a></li>
                </ul>
            </div>
            <div class="footerContent">
                <h3 class="footerHeader">Corporate Info</h3>
                <ul class="footerMenu">
                    <li class="footerLinks"><a href="/">Careers</a></li>
                    <li class="footerLinks"><a href="/">About</a></li>
                    <li class="footerLinks"><a href="/">Press</a></li>
                    <li class="footerLinks">
                        <a href="/">Investor Relations</a>
                    </li>
                </ul>
            </div>
        </div>
        <i>Copyright &copy; 2022, JavaScript Junkies</i>
    </footer>
</div>
