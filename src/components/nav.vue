<template>
    <nav class="header-navbar navbar-expand-lg navbar navbar-with-menu navbar-brand-center navbar-light fixed-top bg-danger" data-nav="brand-center">
        <div class="navbar-header d-xl-block d-none">
            <ul class="nav navbar-nav flex-row">
                <li class="nav-item">
                    <a class="navbar-brand" href="/">
                        <div class="brand-logo"></div>
                        <h2 class="brand-text mb-0">aaa</h2>
                    </a>
                </li>
            </ul>
        </div>
        <div class="navbar-wrapper">
            <div class="navbar-container content">
                <div class="navbar-collapse" id="navbar-mobile">
                    <div class="mr-auto float-left bookmark-wrapper d-flex align-items-center">
                        <ul class="nav navbar-nav">
                            <li class="nav-item mobile-menu mr-auto"><a class="nav-link nav-menu-main menu-toggle" href="#"><i class="bx bx-menu"></i></a></li>
                        </ul>
                        <ul class="nav navbar-nav bookmark-icons">
                            <li class="nav-item d-none d-lg-block">
                                <a href="tel:{{config.phone}}" class="nav-link nav-link-expand" target="_blank"><i class="ficon bx bx-phone"></i> <span class="d-lg-inline d-none">123123</span></a>
                            </li>
                        </ul>
                    </div>
                    <ul class="nav navbar-nav float-right d-flex align-items-center">
                        <li class="nav-item d-none d-lg-block">
                            <a href="{{config.youtube_channel}}" class="nav-link nav-link-expand" target="_blank"><i class="bx bxl-youtube bx-md"></i></a>
                        </li>
                        <li class="nav-item d-none d-lg-block">
                            <a href="{{config.fb_page}}" class="nav-link nav-link-expand" target="_blank"><i class="bx bxl-facebook bx-md"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
    <div class="header-navbar navbar-expand-sm navbar navbar-horizontal navbar-fixed navbar-light navbar-without-dd-arrow" role="navigation" data-menu="menu-wrapper">
        <div class="navbar-header d-xl-none d-block">
            <ul class="nav navbar-nav flex-row">
                <li class="nav-item mr-auto"><a class="navbar-brand" href="/">
                        <div class="brand-logo"></div>
                        <h2 class="brand-text mb-0">test</h2>
                    </a></li>
                <li class="nav-item nav-toggle"><a class="nav-link modern-nav-toggle pr-0" data-toggle="collapse"><i class="bx bx-x d-block d-xl-none font-medium-4 primary toggle-icon"></i></a></li>
            </ul>
        </div>
        <div class="shadow-bottom"></div>
        <div class="navbar-container main-menu-content" data-menu="menu-container">
            <ul class="nav navbar-nav" id="main-menu-navigation" data-menu="menu-navigation" data-icon-style="filled">
                <li class="dropdown nav-item">
                    <a class="nav-link" href="/">
                        <i class=""></i>
                        <span>hello</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    name: 'nav',
    props: {}
}
</script>