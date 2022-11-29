<style>
    .bg-rainbow {
        background-image: linear-gradient(124deg, #ff2400, #e81d1d, #e8b71d, #e3e81d, #1de840, #1ddde8, #2b1de8, #dd00f3, #dd00f3);
        /* transition: ease-in-out 1s; */
        animation: rainbow 5s infinite ease-in-out;
        background-size: 2000% 2000%;
    }

    @keyframes rainbow {
        0%, 100%{
            background-position: 0% 82%;
        }
        50% {
            background-position: 100% 19%;
        }
    }
</style>

<div class="w-full h-screen
            flex flex-col space-y-8 justify-center items-center
            text-white font-bold">
    <h1 class="text-9xl text-transparent bg-clip-text bg-rainbow italic">
        Hello world!
    </h1>
    <p class="text-4xl">
        This is a test for <a class="text-blue-400 underline" href="https://github.com/features/codespaces">GitHub Codespaces!</a>
    </p>

    <p class="text-xl">
        <a class="text-gray-600 hover:text-gray-500 underline" href="/about">About Page</a>
    </p>
</div>
