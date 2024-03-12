<script>
</script>

<!-- svelte-ignore missing-declaration -->
<header class="flex flex-col relative z-20">
    <div
        class=" max-w-[1400px] felx mx-auto w-full flex items-center justify-between p-4 py-6"
    >
        <a href="/" class="w-[108px] h-[27px] gap-4 flex">
            <div class="flex flex-row w-[108px] h-[27px] gap-[4px]">
                <img
                    src="src/Icon.png"
                    alt="Duggup"
                    class="w-[27px] h-[27px]"
                />

                <h1 class="font-semibold w-[76px] h-[21px]">Duggup</h1>
            </div>
        </a>

        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            
            <a 
            
                href="#home"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Home</a
            >
            <a
                href="#Explore"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Explore</a
            >
            <a
                href="#Learn"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Learn</a
            >
            <button class="specialBtn">post</button>
        </nav>
    </div>
</header>
