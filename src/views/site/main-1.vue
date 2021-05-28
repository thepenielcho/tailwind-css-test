<template>
    <div class="m-12 max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-4xl md:h-100 post-box">
    <div class="md:flex">
        <div class="md:flex-shrink-0">
        <img class="h-80 w-full object-cover md:h-80 md:w-80" src="@/assets/expic0.jpg" alt="Man looking at item at a store">
        </div>
        <div class="p-8">
        <div class="tracking-wide text-sm text-indigo-500 font-semibold cont1">Featured</div> <span class="tracking-wide text-sm text-indigo-500 font-semibold cont1-1">&nbsp;</span>
        <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline cont2">선에서 자유로워지기</a>
        <p class="mt-2 text-gray-500 cont3">Tailwind CSS 설치시 자꾸 오류가 나서 포기하고는 했다. 그럼에도 Tailwind는 너무 매력적인 라이브러리이기 때문에 관련한 해결 경험을 공유하고자 한다.</p>
        </div>
    </div>
    </div>
</template>

<style scoped>
    .temp-text {
        font-family: 'Inter';
        font-weight: 900;
        font-size: 2rem;
        margin-bottom: 4rem;
    }
    div .cont1 {
        font-family: 'Inter';
        color: #2D90FF;
        display: inline-block;
    }
    div .cont1-1 {
        color: #000000;
        font-family: 'Inter';
    }
    div .cont2 {
        font-size: 1.5rem;
        font-weight: 500;
    }
    div .cont3 {
        font-size: 1rem;
    }
</style>