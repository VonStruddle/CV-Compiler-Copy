<template>
    <div>
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a class="navbar-item" href="/">
                    <div class="logo-image"></div>
                    <span class="has-text-weight-bold">CV Compiler</span>
                </a>
            </div>

            <div class="navbar-menu">
                <div class="navbar-end">
                    <a href="#" class="navbar-item">
                        How it works
                    </a>
                    <a href="#" class="navbar-item">
                        Pricing
                    </a>
                    <a href="#" class="navbar-item">
                        Who's it for?
                    </a>
                    <a class="navbar-item">
                        <svg id="icon-login" viewBox="0 0 15 15" width="100%" height="100%">
                            <path fill-rule="nonzero" d="M.75 0v15h12.5V9.375H12v4.375H2V1.25h10v4.375h1.25V0H.75zm7.187 4.375L5.242 7.051l-.43.449.43.45 2.695 2.675.88-.879-1.622-1.621H14.5v-1.25H7.195l1.621-1.621-.879-.879z"></path>
                        </svg>
                        <span>Log in</span>
                    </a>
                    <div class="navbar-item">
                        <a class="button is-outlined is-animated">
                            <svg id="icon-upload" viewBox="0 0 11 15" width="100%" height="100%">
                                <path fill-rule="nonzero" d="M5.4.356L4.969.77l-4.2 4.2.862.862L4.8 2.662V12.6H6V2.662l3.169 3.17.862-.863-4.2-4.2L5.4.356zM0 13.8V15h10.8v-1.2H0z"></path>
                            </svg>
                            <span>Upload your CV</span>
                        </a>
                    </div>
                </div>
            </div>
        </nav>
    </div>
</template>

<style lang="scss" scoped>
.navbar {
    padding: 25px 40px 15px 40px;
}
svg {
    -webkit-transition: all .3s;
    -o-transition: all .3s;
    transition: all .3s;
    width: 15px;
    height: 15px;
    margin-right: 5px;
}
#icon-login {
    transform: scale(-1, 1);
}
a {
    &:hover {
        color: #473BE7;
        background-color: transparent;

        svg {
            fill: #473BE7;
        }
    }
}
.button {
    border-radius: 0;
    padding: 26px 33px;
    font-size: 17px;
    font-weight: 500;
    line-height: 1;
    text-transform: uppercase;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    border: 2px solid #0bda8f;
    background-color: #0bda8f;
    cursor: pointer;
    -webkit-transition: all .3s;
    -o-transition: all .3s;
    transition: all .3s;

    &.is-outlined {
        color: #000;
        border: 2px solid #000;
        background-color: transparent;

        &:hover {
            color: #fff;
            background-color: #000;

            svg {
                fill: #fff;
            }
        }
    }
}
.logo-image {
    background-image: url('~static/logo.png');
    width: 50px;
    height: 37px;
    background-repeat: no-repeat;
    background-size: contain;
    margin-right: 10px;
}
</style>

