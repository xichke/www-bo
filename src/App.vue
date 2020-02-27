<template>
    <div id="app">
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
                                    <a href="tel:123123" class="nav-link nav-link-expand" target="_blank"><i class="ficon bx bx-phone"></i> <span class="d-lg-inline d-none">123123</span></a>
                                </li>
                            </ul>
                        </div>
                        <ul class="nav navbar-nav float-right d-flex align-items-center">
                            <li class="nav-item d-none d-lg-block">
                                <a href="/" class="nav-link nav-link-expand" target="_blank"><i class="bx bxl-youtube bx-md"></i></a>
                            </li>
                            <li class="nav-item d-none d-lg-block">
                                <a href="/" class="nav-link nav-link-expand" target="_blank"><i class="bx bxl-facebook bx-md"></i></a>
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
        <div class="app-content content">
            <div class="content-overlay"></div>
            <div class="content-wrapper">
                <div class="content-header row">
                    <div class="content-header-left col-12 mb-2 mt-1">
                        <div class="row breadcrumbs-top">
                            <div class="col-12">
                                <h5 class="content-header-title float-left pr-1 mb-0">Basic Card</h5>
                                <div class="breadcrumb-wrapper col-12">
                                    <ol class="breadcrumb p-0 mb-0">
                                        <li class="breadcrumb-item"><a href="index.html"><i class="bx bx-home-alt"></i></a>
                                        </li>
                                        <li class="breadcrumb-item"><a href="#">Card</a>
                                        </li>
                                        <li class="breadcrumb-item active">Basic Card
                                        </li>
                                    </ol>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="content-body">
                    <div class="alert bg-rgba-primary">
                        <i class="bx bx-info-circle mr-1 align-middle"></i>
                        <span class="align-middle">
                            Click <a href="https://getbootstrap.com/docs/4.3/components/card/" target="_blank"><u>here</u></a>
                            for more info on cards.
                        </span>
                    </div>
                    <router-view />
                </div>
            </div>
        </div>
    </div>
</template>