<template>

    <header class="w-full flex flex-row justify-between items-end py-2 px-4 lg:px-32 lg:py-4 bg-gray-100">
        <div class="flex flex-row justify-between items-end">
            <a href="#" class=" lg:mr-4">
            <img src="../assets/imgs/logo.png" class=" w-28" alt="logo images">
            </a>
            <div class="here max-lg:hidden">
                <a href="#" class="text-[#242464] text-lg hover:text-[#5555FF] font-normal mr-8">About us</a>
                <a href="#" class="text-[#242464] text-lg hover:text-[#5555FF] font-normal mr-8">Download</a>
                <a href="#" class="text-[#242464] text-lg hover:text-[#5555FF] font-normal">Contact</a>
            </div> 
        </div>
        
        <div class="max-lg:hidden">
            <a href="#" class="text-[#5555FF] mr-6 text-lg font-semibold hover:text-[#242464]">Log in</a>
            <a href="#" class="bg-[#5555FF] text-white py-2 px-4 rounded-lg text-lg font-semibold hover:bg-[#FCAF3B] duration-300">Primary action</a>
        </div>
        <div class="links lg:hidden">
            <span id="menu" class=" w-6 cursor-pointer">
                <span class="bg-black mb-2"></span>
                <span class="bg-black mb-2"></span>
                <span class="bg-black"></span>
            </span>
            <ul>
                <li><a href="#" class="text-[#242464]">About us</a></li>
                <li><a href="#" class="text-[#242464]">Download</a></li>
                <li><a href="#" class="text-[#242464]">Contact</a></li>
                <li><a href="#" class="text-[#5555FF]">Log in</a></li>
                <li><a href="#" class="text-[#5555ff]">Primary action</a></li>
            </ul>
        </div>
        
    </header>

    <main class=" bg-gray-100">

        <section class="flex flex-col w-full items-end justify-center gap-6 px-4 py-8 lg:py-20 lg:px-32 lg:gap-6 lg:flex-row lg:justify-between">
            
            <div class="">
                <h2 class=" text-5xl text-[#171740] font-semibold lg:text-6xl lg:mb-8 mb-6">
                    Lorem ipsum dolor sit amet.
                </h2>
                <p class=" text-lg font-normal text-[#242464] lg:text-2xl lg:mb-8 mb-6">
                    Praesent placerat ipsum nec mi maximus, vel cursus mauris cursus. Vivamus cursus ante eget orci egestas malesuada.
                </p>
                <div class="flex flex-col justify-center items-center gap-4 lg:flex-row lg:justify-start">
                    <a href="#" class="bg-[#5555FF] text-white py-2 px-4 w-full text-center rounded-lg text-lg font-semibold lg:w-auto lg:mr-4 hover:bg-[#FCAF3B] duration-300">Primary action</a>
                    <a href="#" class="text-[#171740] font-semibold text-lg hover:text-[#5555FF]">Secondary action</a>
                </div>
            </div>
            
            <img src="https://via.placeholder.com/400x225.png" alt="place holder image" class=" rounded-2xl lg:w-[588px]">
        </section>
    
        <section class=" px-4 flex flex-col items-center gap-8 lg:px-32 lg:py-12 lg:items-start">
            <h3 class="text-[#171740] text-3xl font-semibold">
                Trusted by
            </h3>
            <div id="imgs" class="flex flex-col gap-8 items-center lg:flex-row lg:items-center lg:gap-6 lg:justify-between">
                <img src="../assets/imgs/Monzo.png"  class="w-48 grayscale hover:grayscale-0 duration-500 hover:scale-105" alt="Monzo logo">
                <img src="../assets/imgs/Zoopla.png" class="w-48 grayscale hover:grayscale-0 duration-500 hover:scale-105 lg:mx-8 " alt="Zoopla logo">
                <img src="../assets/imgs/Google.png" class="w-48 grayscale hover:grayscale-0 duration-500 hover:scale-105 lg:mx-8 " alt="Google logo">
                <img src="../assets/imgs/Nike.png"   class="w-48 grayscale hover:grayscale-0 duration-500 hover:scale-105 lg:mx-8 " alt="Nike logo">
                <img src="../assets/imgs/Amazon.png" class="w-48 grayscale hover:grayscale-0 duration-500 hover:scale-105" alt="Amazon logo">
            </div>
        </section>
    
        <section class="flex flex-col items-start py-8 px-4 gap-6 lg:flex-row lg:px-32 lg:py-12">
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-d duration-300">
                <img src="https://via.placeholder.com/400x225.png" class=" rounded-2xl" alt="place holder image">
                <div class="flex flex-col gap-2 items-start px-2 py-4">
                    <h3 class=" text-2xl font-semibold text-[#171740]">
                        Lorem ipsum
                    </h3>
                    <p class="text-[#242464] text-lg font-normal">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
                <button class="w-full bg-[#5555ff] py-3 px-8 font-semibold text-white rounded-lg duration-300">
                    Button
                </button>
            </div>
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-d duration-300">
                <img src="https://via.placeholder.com/400x225.png" class=" rounded-2xl" alt="place holder image">
                <div class="flex flex-col gap-2 items-start px-2 py-4">
                    <h3 class=" text-2xl font-semibold text-[#171740]">
                        Lorem ipsum
                    </h3>
                    <p class="text-[#242464] text-lg font-normal">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
                <button class="w-full bg-[#5555ff] py-3 px-8 font-semibold text-white rounded-lg duration-300">
                    Button
                </button>
            </div>
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-d duration-300">
                <img src="https://via.placeholder.com/400x225.png" class=" rounded-2xl" alt="place holder image">
                <div class="flex flex-col gap-2 items-start px-2 py-4">
                    <h3 class=" text-2xl font-semibold text-[#171740]">
                        Lorem ipsum
                    </h3>
                    <p class="text-[#242464] text-lg font-normal">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
                <button class="w-full bg-[#5555ff] py-3 px-8 font-semibold text-white rounded-lg duration-300">
                    Button
                </button>
            </div>
        </section>
    
        <section>

        </section>
    
    </main>

    <footer class=" bg-gray-100">

    </footer>

</template>

<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  if ('IntersectionObserver' in window) {
    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show')
        } else {
          entry.target.classList.remove('show')
        }
      })
    })

    const hiddenElements = document.querySelectorAll('.manga-d')
    hiddenElements.forEach((el) => observer.observe(el))
  } else {
    console.log('IntersectionObserver not supported')
  }
})
</script>


<style scoped>

.links {
    position: relative;
}

header #menu span:nth-child(2){
    width: 100%;
}

header #menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-end;
}

header #menu span {
    background-color: #000;
    height: 2px;
}

header #menu span:first-child{
    width: 50%;
    transition: 0.3s;
}

header #menu span:nth-child(2){
    width: 100%;
}

header #menu span:last-child{
    width: 50%;
    transition: 0.3s;
}

header #menu:hover span:first-child{
    width: 100%;
}

header #menu:hover span:last-child{
    width: 100%;
}
.links ul {
    list-style: none;
    margin: 0;
    padding: 0;
    background-color: #f6f6f6;
    position: absolute;
    right: 0;
    min-width: 200px;
    top: calc(100% + 15px);
    display: none;
    z-index: 1;
}
.links ul::before {
    content: "";
    border-width: 10px;
    border-style: solid;
    border-color: transparent transparent #f6f6f6 transparent;
    position: absolute;
    right: 5px;
    top: -20px;
} 
.links:hover ul{
    display: block;
}
.links ul li a {
    display: block;
    text-decoration: none;
    color: #242464;
    padding: 15px;
    transition: 0.3s;
}
.links ul li a:hover{
    padding-left: 25px;
}
.links ul li:not(:last-child) a {
    border-bottom: 1px solid #ccc;
}

.manga-d {
    opacity: 0;
    transition: all 1s;
    transform: translateX(-100%);
    filter: blur(2px);
}
.manga-d:hover button {
    background-color: #FCAF3B;
}

.show {
    opacity: 1;
    filter: blur(0px);
    transform: translateX(0);
}

.manga-d:nth-child(2){
    transition-delay: 200ms;
}
.manga-d:nth-child(3){
    transition-delay: 400ms;
}
</style>