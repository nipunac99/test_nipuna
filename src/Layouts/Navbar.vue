<template>
    <header
        style="position: fixed; top: 0; left: 0; width: 100%; display:flex; align-items:center; justify-content: space-between; transition: 0.6s;  padding: 10px 100px;">
        <nav class="navbar navbar-expand-md">

            <a class="navbar-brand logo" href="#"
                style="position: relative; font-weight: 700; color: #fff; text-transform: uppercase; letter-spacing: 2px; transition: 0.6s;">Company
                Logo</a>

            <button class="navbar-toggler border-0 shadow-none" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarNav" aria-controls="navbarNav" aria-hexpanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav"
                    style="display: flex; position: relative;  justify-content: center; align-items: center;">
                    <li class="nav-item dropdown" style=" position: relative;  list-style: none;">
                        <a class="nav-link dropdown-toggle text-uppercase" href="#" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false"
                            style=" position: relative;  margin: 0 15px; color: #fff;  letter-spacing: 2px;  font-weight: 500px; transition: 0.6s; font-size:12px;">
                            English
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Spanish</a></li>
                            <li><a class="dropdown-item" href="#">Tamil</a></li>
                            <li><a class="dropdown-item" href="#">Sinhala</a></li>

                        </ul>
                    </li>
                    <li class="nav-item" style=" position: relative;  list-style: none;">
                        <a class="nav-link active"
                            style=" position: relative;  margin: 0 15px; color: #fff;  letter-spacing: 2px;  font-weight: 500px; transition: 0.6s;"
                            aria-current="page" href="#">About Us</a>
                    </li>
                    <li class="nav-item" style=" position: relative;  list-style: none;">
                        <a class="nav-link active"
                            style=" position: relative;  margin: 0 15px; color: #fff;  letter-spacing: 2px;  font-weight: 500px; transition: 0.6s;"
                            href="#">Features</a>
                    </li>
                    <li class="nav-item" style=" position: relative;  list-style: none;">
                        <a class="nav-link active"
                            style=" position: relative;  margin: 0 15px; color: #fff;  letter-spacing: 2px;  font-weight: 500px; transition: 0.6s;"
                            href="#">Contact</a>
                    </li>

                </ul>
            </div>

        </nav>

        <img src="/Icons/hamburger-menu-icon.svg" alt="" class="hamburger-menu-icon"
            style="width: 25px; cursor:pointer">



    </header>



</template>

<script>
export default {
    mounted() {
        window.addEventListener("scroll", function () {
            var header = document.querySelector("header");
            header.classList.toggle("sticky", window.scrollY > 0);
        })

    }
}
</script>

<style></style>