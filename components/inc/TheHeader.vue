<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-light">
            <div class="container-fluid">
                <NuxtLink class="navbar-brand" to="/">Navbar</NuxtLink>

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <NuxtLink class="nav-link active" to="/">Home</NuxtLink>
                        </li>
                        <li class="nav-item">
                            <NuxtLink class="nav-link" to="/about">About</NuxtLink>
                        </li>
                        <li class="nav-item">
                            <NuxtLink class="nav-link" to="/contact">Contact</NuxtLink>
                        </li>
                        <li class="nav-item dropdown">
                            <NuxtLink class="nav-link dropdown-toggle" to="#" id="navbarDropdown" role="button"
                                data-bs-toggle="dropdown">Services</NuxtLink>
                            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <li>
                                    <NuxtLink class="dropdown-item" to="/java">Java</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink class="dropdown-item" to="/android">Android</NuxtLink>
                                </li>
                                <li>
                                    <hr class="dropdown-divider" />
                                </li>
                                <li>
                                    <NuxtLink class="dropdown-item" to="#">Something else here</NuxtLink>
                                </li>
                            </ul>
                        </li>
                    </ul>
                    <form class="d-flex" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
                        <button class="btn btn-outline-success" type="submit">
                            Search
                        </button>
                    </form>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "TheHeader",
};
</script>

<style>
</style>