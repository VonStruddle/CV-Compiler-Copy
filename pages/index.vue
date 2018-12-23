<template>
    <div id="#top">
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
                        <a class="button is-outlined">
                            <svg id="icon-upload" viewBox="0 0 11 15" width="100%" height="100%">
                                <path fill-rule="nonzero" d="M5.4.356L4.969.77l-4.2 4.2.862.862L4.8 2.662V12.6H6V2.662l3.169 3.17.862-.863-4.2-4.2L5.4.356zM0 13.8V15h10.8v-1.2H0z"></path>
                            </svg>
                            <span>Upload your CV</span>
                        </a>
                    </div>
                </div>
            </div>
        </nav>

        <section class="hero">
            <div class="hero-body">
                <div class="container">
                    <div class="columns">
                        <div class="column">
                            <img src="~static/home-hero.svg" alt="CV Compiler">
                        </div>
                        <div class="column">
                            <vue-typed-js
                                :strings="headlineStrings"
                                :loop="true"
                                :typeSpeed="100"
                                :backSpeed="50"
                            >
                                <h1 class="title font-secondary">
                                    Get a Tech CV worth a job at
                                    <span class="typing"></span>
                                </h1>
                            </vue-typed-js>
                            <p class="has-text-black">
                                We’ve analyzed <i>1M tech resumes</i> to create an online revision tool that scans your dev resume and indicate its weak points in real time.
                            </p>
                            <a href="#" class="button">
                                <span class="button-text">
                                    Improve your resume
                                </span>
                            </a>
                            <p>DOC, DOCX, PDF — supported formats</p>
                            <div class="featured-on-wrapper">
                                <span>Featured on</span>
                                <a href="">
                                    <svg id="tech-crunch-logo" viewBox="0 0 171 24" width="100%" height="100%">
                                        <g fill="none" fill-rule="evenodd">
                                            <path fill="#0A9600" d="M63.974 9.377V20h-3.881V9.377h-3.921v-3.38h11.723v3.38zM72.193 11.938c-.82 0-1.28.56-1.4 1.6h3.001c-.18-1.06-.54-1.6-1.6-1.6m4.76 3.841h-6.16c.12 1.16.798 1.68 1.78 1.68.92 0 1.68-.2 2.72-.74l1.38 2.301c-1.3.759-2.64 1.2-4.28 1.2-3.162 0-4.902-2.241-4.902-5.462 0-3.62 2.04-5.481 4.801-5.481 2.88 0 4.681 1.901 4.681 5.801 0 .301 0 .521-.02.701M83.653 20.22c-3.08 0-4.92-1.96-4.92-5.501 0-3.221 1.64-5.441 5-5.441 1.981 0 3.121.92 4.041 2.4l-2.48 1.88c-.5-.92-.84-1.36-1.62-1.36-.92 0-1.38.92-1.38 2.58 0 1.662.5 2.52 1.48 2.52.68 0 1.16-.38 1.82-1.36l2.28 1.78c-1.22 1.802-2.36 2.502-4.22 2.502M95.934 20v-5.962c0-1.36-.46-1.72-1.2-1.72-.761 0-1.221.36-1.221 1.68V20h-3.6V6.857l3.6-1.44v4.78c.66-.5 1.4-.92 2.64-.92 2.302 0 3.402 1.54 3.402 4.301V20h-3.621z"></path>
                                            <path fill="#000" d="M108.174 20.22c-4.161 0-6.382-3.081-6.382-7.222 0-4.501 2.64-7.221 6.402-7.221 3.44 0 4.8 1.48 5.76 4.12l-3.52 1.38c-.5-1.3-.98-2.12-2.26-2.12-1.62 0-2.32 1.62-2.32 3.84 0 2.142.679 3.842 2.36 3.842 1.22 0 1.74-.66 2.5-1.98l3.28 1.74c-.94 1.84-2.5 3.62-5.82 3.62M122.853 13.458c-.46-.5-.98-.88-1.68-.88-.882 0-1.422.42-1.422 1.7V20h-3.6V9.497h3.6v.76c.621-.6 1.322-.98 2.242-.98.76 0 1.28.18 1.7.44l-.84 3.741zM131.413 20v-.701c-.64.5-1.4.921-2.62.921-2.3 0-3.4-1.54-3.4-4.302V9.497h3.62v5.962c0 1.359.46 1.72 1.2 1.72s1.2-.361 1.2-1.681V9.497h3.621V20h-3.62zM143.653 20v-5.962c0-1.36-.46-1.72-1.2-1.72-.76 0-1.22.36-1.22 1.68V20h-3.6V9.497h3.6v.7c.66-.5 1.4-.92 2.64-.92 2.301 0 3.401 1.54 3.401 4.301V20h-3.62zM154.292 20.22c-3.08 0-4.921-1.96-4.921-5.501 0-3.221 1.641-5.441 5.001-5.441 1.981 0 3.121.92 4.041 2.4l-2.48 1.88c-.5-.92-.841-1.36-1.62-1.36-.921 0-1.381.92-1.381 2.58 0 1.662.5 2.52 1.48 2.52.68 0 1.16-.38 1.82-1.36l2.281 1.78c-1.22 1.802-2.361 2.502-4.221 2.502M166.572 20v-5.962c0-1.36-.46-1.72-1.2-1.72-.76 0-1.22.36-1.22 1.68V20h-3.6V6.857l3.6-1.44v4.78c.66-.5 1.4-.92 2.64-.92 2.301 0 3.401 1.54 3.401 4.301V20h-3.62z"></path>
                                            <path fill="#0A9600" d="M0 0v8h8v16h8V8h8V0zM32 16V8h-8v16h24v-8zM32 8h16V0H32z"></path>
                                        </g>
                                    </svg>
                                </a>
                                <a href="">
                                    <span class="ph-wrapper">

                                        <svg id="ph-badge" viewBox="0 0 21 28" width="100%" height="100%">
                                            <g fill="none" fill-rule="evenodd">
                                                <path fill="#DE7818" fill-rule="nonzero" d="M4.33 16.364L.328 24.9c-.126.258.007.42.427.34l3.258-.708a.244.244 0 0 1 .317.17l1.467 3.007c.14.324.302.39.428.133l4.26-8.934-6.155-2.544zm12.34 0l4.002 8.536c.133.258-.007.42-.427.34l-3.258-.708a.246.246 0 0 0-.317.17l-1.467 3.007c-.14.324-.295.39-.428.133l-4.26-8.934 6.155-2.544z"></path>
                                                <path fill="#B35454" d="M9.298 21.392c0 .007-.014 0-.029 0a10.44 10.44 0 0 1-5.97-2.742c-.008-.008-.03-.015-.023-.023l.184-.39c.008-.015.022.022.03.03 1.577 1.466 3.767 2.388 6.007 2.66.008 0 .023 0 .023.008l-.222.457z"></path>
                                                <circle cx="10.5" cy="10.489" r="10.489" fill="#F0CD0A"></circle>
                                                <circle cx="10.5" cy="10.489" r="9.045" fill="#D2B309"></circle>
                                                <circle cx="10.75" cy="10.75" r="8.75" fill="#E3C101"></circle>
                                                <path fill="#FFF2B5" d="M9.45 14.755h2.15V6.3H9.45L7.3 7.765v1.851L9.34 8.24h.11z"></path>
                                                <path fill="#FFF" fill-opacity=".2" d="M12.97 3.089a7.604 7.604 0 0 1 .353 14.698c2.035-1.555 3.384-4.209 3.384-7.224 0-3.184-1.504-5.963-3.738-7.474h.001z"></path>
                                                <path fill="#B35454" d="M11.702 21.392c.007.007.022 0 .029 0 2.293-.288 4.4-1.21 5.986-2.728.007-.007.029-.014.022-.022l-.185-.39c-.007-.015-.022.022-.03.029-1.577 1.467-3.773 2.374-6.021 2.646-.008 0-.023 0-.023.008l.222.457z"></path>
                                            </g>
                                        </svg>
                                        <span>
                                            #1 Product of the Day<br>
                                            on ProductHunt
                                        </span>
                                    </span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="section is-zig-zag">
            <div class="container">
                <div class="columns">
                    <div class="column">
                        <figure class="image">
                            <img src="~static/upload-illustration.svg" alt="Upload your CV">
                        </figure>
                        <h2 class="title font-secondary">
                            Upload<br>
                            your CV
                        </h2>
                        <p>
                            Upload your CV <strong>in English</strong> as a PDF or DOC(X) file. The max file size is 5MB.
                        </p>
                    </div>
                    <div class="column is-opposed">
                        <figure class="image">
                            <img src="~static/unlock-illustration.svg" alt="Unlock the full toolkit">
                        </figure>
                        <h2 class="title font-secondary">
                            Unlock<br>
                            the full toolkit
                        </h2>
                        <p>
                            Want to craft a killer tech resume and cover letter? CV Compiler has everything you need in one place.
                        </p>
                    </div>
                </div>
                <div class="columns">
                    <div class="column">
                        <figure class="image">
                            <img src="~static/examination-illustration.svg" alt="Improve your resume today">
                        </figure>
                        <h2 class="title font-secondary">
                            Improve<br>
                            your resume <i>today</i>
                        </h2>
                        <p>
                            It’s a huge time saver. We’ll show you what to improve and how to do it.
                        </p>
                    </div>
                    <div class="column is-opposed">
                        <figure class="image">
                            <img src="~static/cv-review-illustration.svg" alt="Get the job you want">
                        </figure>
                        <h2 class="title font-secondary">
                            Get<br>
                            the job you want
                        </h2>
                        <p>
                            A good resume is only half the battle, but it will definitely increase your chances of getting interviews.
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    data() {
        return {
            headlineStrings: ["Facebook", "Amazon", "Netflix", "Google"],
        };
    },
    head() {
        return {
            title: "CV Complier copy"
        }
    },
}
</script>


<style lang="scss" scoped>
.font-secondary {
    font-family: "Space Mono", sans-serif;
}
.navbar {
    padding: 25px 40px 15px 40px;
}
svg {
    overflow: hidden;
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
.hero {
    h1 {
        font-size: 68px;
        line-height: 1.13;
        margin-bottom: 35px;
    }

    p {
        margin-bottom: 60px;
    }

    .button {
        width: 425px;
        height: 65px;
        margin-bottom: 15px;
        font-size: 19px;
        position: relative;

        .button-text {
            color: #000;
            -webkit-transition: all .3s;
            -o-transition: all .3s;
            transition: all .3s;
        }

        &:hover {
            background-color: #0bda8f;

            .button-text {
                transform: translate(-10px, -10px);
            }
        }

        &::before {
            content: "";
            display: block;
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            border: 3px solid transparent;
            -webkit-transition: all .3s;
            -o-transition: all .3s;
            transition: all .3s;
        }

        &:hover::before {
            transform: translate(-10px, -10px);
            border-color: #000;
        }

        &::after {
            content: "";
            display: block;
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            border: 3px solid transparent;
            transition: all .3s;
            z-index: -1;
        }

        &:hover::after {
            transform: translate(10px, 10px);
            border-color: #473BE7;
        }
    }
}
.featured-on-wrapper {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
#tech-crunch-logo {
    width: 171px;
    height: 24px;
}
#ph-badge {
    width: 21px;
    height: 28px;
    margin-right: 13px;
}
.ph-wrapper {
    display: flex;
    align-items: center;

    span {
        font-size: 13px;
        color: #000;

        &:hover {
            color: #473BE7;
        }
    }
}
.is-zig-zag {
    .column {
        margin-bottom: 190px;

        &.is-opposed {
            margin-left: 180px;
            -webkit-transform: translate(0, 180px);
            -ms-transform: translate(0, 180px);
            transform: translate(0, 180px);
            margin-bottom: 0;
        }
    }

    .image {
        max-width: 180px;
        margin-bottom: 35px;
    }

    .title {
        margin-bottom: 20px;
        line-height: 1.25;
        font-size: 40px;

        &::before {
            -webkit-box-sizing: inherit;
            box-sizing: inherit;
            counter-increment: section;
            content: "0" counter(section);
            position: absolute;
            left: -35px;
            top: 248px;
            font-size: 17px;
            opacity: .3;
        }
    }
}
</style>
