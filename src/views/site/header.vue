<template>
    <div class="p-3 flex items-center justify-between">
        <div class="flex items-center">
            <button class="rounded-full hover:bg-light p-3 flex items-center justify-center logo-box" type="button" name="button">
                <img src="@/assets/logo.png" alt="logo" class="h-6 w-6">
            </button>
            <div>
                <a href="#" class="logoTitle">penieLog</a>
            </div>
        </div>
        <div class="flex items-center">
            <div class="flex">
                About
            </div>
            <div class="flex">
                Projects
            </div>
            <div class="flex">
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
</style>