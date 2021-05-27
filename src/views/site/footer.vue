<template>
    <div class="p-2 flex items-center justify-center">
        <div class="flex items-center">
            <button class="rounded-full hover:bg-light p-3 flex items-center justify-center logo-box" type="button" name="button">
                <img src="@/assets/logo.png" alt="logo" class="h-6 w-6">
            </button>
            <div>
                <a href="#" class="logoTitle">penieLog</a>
            </div>
        </div>
    </div>
    <div class="navFoot flex items-center justify-center">
        <div class="flex items-center">
            <div class="flex navMenu">
                Blog
            </div>
            <div class="flex navMenu">
                Projects
            </div>
            <div class="flex navMenu-last">
                GitHub
            </div>
        </div>
    </div>
        <div class="copyright flex items-center justify-center">
        <div class="flex items-center">
            <div class="flex copyright-font">
                © 2021 Peniel Cho. All Right Reserved. Published with Vue Press.
            </div>
        </div>
    </div>
</template>

<style scoped>
    .logo-box {
        outline: none;
    }
    .logoTitle {
        font-family: 'Inter';
        font-weight: 700;
        font-size: 20px;
        padding-right: 12px;
    }
    .navMenu {
        font-family: 'Inter';
        font-weight: 400;
        font-size: 0.9rem;
        margin-right: 1rem;
    }
    .navMenu-last {
        font-family: 'Inter';
        font-weight: 400;
        font-size: 0.9rem;
    }
    .navFoot {
        padding: 0.5rem 1rem 2.5rem;
    }
    .copyright {
        padding: 0rem 0rem 2rem;
    }
    .copyright-font {
        font-family: 'Inter';
        font-weight: 300;
        font-size: 0.75rem;
    }
</style>
