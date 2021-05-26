<template>
    <div class="p-6 flex items-center justify-between">
        <div class="flex items-center">
            <button class="rounded-full hover:bg-light p-3 flex items-center justify-center logo-box" type="button" name="button">
                <img src="@/assets/logo.png" alt="logo" class="h-6 w-6">
            </button>
            <div>
                <a href="#" class="logoTitle">penieLog</a>
            </div>
        </div>
        <div class="flex items-center">
            <div class="flex navMenu">
                About
            </div>
            <div class="flex navMenu">
                Projects
            </div>
            <div class="flex navMenu">
                Blog
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
    }
    .navMenu {
        font-family: 'Inter';
        font-weight: 400;
        font-size: 0.9rem;
        margin-right: 1rem;
    }
</style>
