<template>

    <!-- <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Navbar</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                aria-expanded="false">
                                Dropdown
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                        </li>
                    </ul>
                    <form class="d-flex" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                </div>
            </div>
        </nav> -->

    <!-- <header>
            <a href="#" class="logo">Company logo</a>

            <ul>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Features</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </header> -->

    <header
        style="position: fixed; top: 0; left: 0; width: 100%; display:flex; align-items:center; justify-content: space-between; transition: 0.6s;  padding: 10px 100px;">
        <nav class="navbar navbar-expand-md">

            <a class="navbar-brand logo" href="#"
                style="position: relative; font-weight: 700; color: #fff; font-size: 2rem;   text-transform: uppercase; letter-spacing: 2px; transition: 0.6s;">Company
                Logo</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
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
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
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