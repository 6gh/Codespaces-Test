<style>
    .bg-rainbow {
        background-image: linear-gradient(90deg, #FF0000 0%, #FF7F00 7%, #FFFF00 14%, #00FF00 21%, #0000FF 28%, #4B0082 35%, #8B00FF 42%, #4B0082 49%, #0000FF 60%, #00FF00 70%, #FFFF00 76%, #FF7F00 87%, #FF0000 100%);
        /* transition: ease-in-out 1s; */
        animation: rainbow 5s infinite ease-in-out;
        background-size: 400% 100%;
    }

    @keyframes rainbow {
        0%, 100% {
            background-position: 0 0;
        }

        50% {
            background-position: 100% 0;
        }
    }
</style>

<div class="bg-black w-full h-screen
            flex flex-col space-y-8 justify-center items-center
            text-white font-bold">
    <h1 class="text-9xl text-transparent bg-clip-text bg-rainbow italic">
        Hello world!
    </h1>
    <p class="text-4xl">
        This is a test for <a class="text-blue-400 underline" href="https://github.com/features/codespaces">GitHub Codespaces!</a>
    </p>
</div>
