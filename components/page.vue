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

    <main class=" bg-gray-100 overflow-hidden">

        <section class="flex flex-col w-full items-end sm:items-center max-sm:items-center justify-center gap-6 px-4 py-8 lg:py-20 lg:px-32 lg:gap-6 lg:flex-row lg:justify-between">
            
            <div class="">
                <h2 class=" text-5xl text-[#171740] font-semibold lg:text-6xl lg:mb-8 mb-6">
                    Lorem ipsum dolor sit amet.
                </h2>
                <p class=" text-lg font-normal text-[#242464] lg:text-2xl lg:mb-8 mb-6">
                    Praesent placerat ipsum nec mi maximus, vel cursus mauris cursus. Vivamus cursus ante eget orci egestas malesuada.
                </p>
                <div class="flex flex-col justify-center items-center gap-4 sm:flex-row sm:justify-center lg:justify-start">
                    <a href="#" class="bg-[#5555FF] text-white py-2 px-4 w-full text-center rounded-lg text-lg font-semibold sm:w-auto lg:mr-4 hover:bg-[#FCAF3B] duration-300">Primary action</a>
                    <a href="#" class="text-[#171740] font-semibold text-lg hover:text-[#5555FF]">Secondary action</a>
                </div>
            </div>
            
            <img src="https://via.placeholder.com/400x225.png" alt="place holder image" class=" rounded-2xl sm:w-[480px] lg:w-[588px]">
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
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-r duration-300">
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
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-r duration-300">
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
            <div class="flex flex-col items-center gap-4 rounded-2xl bg-white p-4 hover:bg-[#5555FF] manga-r duration-300">
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
    
        <section class="flex flex-col items-start justify-center py-12 px-4 gap-6 lg:flex-row lg:px-32 lg:py-12">

            <div class=" flex flex-col items-start py-6 px-8 gap-4 bg-white rounded-2xl shadow-md w-full hover:bg-[#5555ff] duration-300 manga-r manga-l">
                <h1 class=" font-semibold text-3xl text-[#171740]">
                    Free
                </h1>

                <p class="flex flex-row gap-2 items-center text-[#171740] font-normal text-3xl">
                    <span class=" font-semibold text-5xl">
                        £0
                    </span>
                    / month
                </p>

                <div class="flex flex-col items-center py-4">
                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>

                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>
                    
                    <p class="font-normal text-[#171740] text-lg">
                        ❌ Lorem ipsum dolor
                    </p>

                </div>

                <button class=" py-2 px-8 bg-gray-50 font-semibold text-lg text-[#171740] w-full rounded-lg duration-300">
                    Sign up
                </button>
            </div>

            <div class=" flex flex-col items-start py-6 px-8 gap-4 bg-white rounded-2xl shadow-md w-full hover:bg-[#5555ff] duration-300 manga-r manga-l">
                <h1 class=" font-semibold text-3xl text-[#171740]">
                    Standard
                </h1>

                <p class="flex flex-row gap-2 items-center text-[#171740] font-normal text-3xl">
                    <span class=" font-semibold text-5xl">
                        £9
                    </span>
                    / month
                </p>

                <div class="flex flex-col items-center py-4">
                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>

                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>
                    
                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>

                </div>

                <button class=" py-2 px-8 bg-gray-50 font-semibold text-lg text-[#171740] w-full rounded-lg duration-300">
                    Sign up
                </button>
            </div>

            <div class=" flex flex-col items-start py-6 px-8 gap-4 bg-white rounded-2xl shadow-md w-full hover:bg-[#5555ff] duration-300 manga-r manga-l">
                <h1 class=" font-semibold text-3xl text-[#171740]">
                    Enterprise
                </h1>

                <p class="flex flex-row gap-2 items-center text-[#171740] font-normal text-3xl">
                    <span class=" font-semibold text-5xl">
                        £16
                    </span>
                    / month
                </p>

                <div class="flex flex-col items-center py-4">
                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>

                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>
                    
                    <p class="font-normal text-[#171740] text-lg">
                        ✔ Lorem ipsum dolor
                    </p>

                </div>

                <button class=" py-2 px-8 bg-gray-50 font-semibold text-lg text-[#171740] w-full rounded-lg duration-300">
                    Sign up
                </button>
            </div>
        </section>
        
        <section class="flex flex-col items-center py-8 px-4 gap-8 lg:px-32 lg:py-12">
            <p class="font-semibold text-4xl text-[#171740] text-center manga-p duration-300">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </p>
            <div class="flex flex-col items-center gap-2">
                <img src="../assets/imgs/Ellipse.png" class=" rounded-[50%] w-16 h-16 manga-p duration-300" alt="place holder image">
                <h3 class="text-[#242464] text-lg font-semibold text-center manga-p duration-300">
                    Jennifer Rowlands
                </h3>
                <p class="text-lg font-normal text-[#242464] text-center manga-p duration-300">
                    Chief Design Office, uxtoast
                </p>
            </div>
        </section>

        <section class="flex flex-col items-center justify-center p-4 gap-4 lg:px-32 lg:py-12 lg:gap-6">

            <div class="flex flex-col items-center p-4 gap-4 lg:flex-row lg:gap-6">

                <div class="flex flex-col justify-center items-start gap-4 order-none manga-r lg:w-[588px] lg:h-60 lg:gap-8 lg:mr-4">
                    <p class="font-semibold text-3xl text-[#171740] order-none text-center lg:text-[40px] lg:text-left">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                    <p class="text-lg font-normal text-[#242464] order-1 text-center lg:text-2xl lg:text-left">
                        Praesent placerat ipsum nec mi maximus, vel cursus mauris cursus. Vivamus cursus ante eget orci egestas malesuada.
                    </p>
                </div>

                <img src="https://via.placeholder.com/400x225.png" class="order-1 rounded-2xl manga-l manga-r lg:w-[588px] lg:h-96" alt="place holder image">

            </div>

            <div class="flex flex-col items-center p-4 gap-4 lg:flex-row lg:gap-6">

                <div class="flex flex-col justify-center items-start gap-4 order-none manga-l manga-r lg:w-[588px] lg:h-60 lg:gap-8 lg:mr-4 lg:order-1">
                    <p class="font-semibold text-3xl text-[#171740] order-none text-center lg:text-[40px] lg:text-left">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                    <p class="text-lg font-normal text-[#242464] order-1 text-center lg:text-2xl lg:text-left">
                        Praesent placerat ipsum nec mi maximus, vel cursus mauris cursus. Vivamus cursus ante eget orci egestas malesuada.
                    </p>
                </div>

                <img src="https://via.placeholder.com/400x225.png" class="order-1 rounded-2xl manga-r lg:w-[588px] lg:h-96 lg:order-none" alt="place holder image">

            </div>

            <div class="flex flex-col items-center p-4 gap-4 lg:flex-row lg:gap-6">

                <div class="flex flex-col justify-center items-start gap-4 order-none manga-r lg:w-[588px] lg:h-60 lg:gap-8 lg:mr-4">
                    <p class="font-semibold text-3xl text-[#171740] order-none text-center lg:text-[40px] lg:text-left">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                    <p class="text-lg font-normal text-[#242464] order-1 text-center lg:text-2xl lg:text-left">
                        Praesent placerat ipsum nec mi maximus, vel cursus mauris cursus. Vivamus cursus ante eget orci egestas malesuada.
                    </p>
                </div>

                <img src="https://via.placeholder.com/400x225.png" class="order-1 rounded-2xl manga-l manga-r lg:w-[588px] lg:h-96" alt="place holder image">

            </div>

        </section>

        <section class="flex flex-col items-center py-8 px-4 gap-6 lg:flex-row lg:items-start lg:py-12 lg:px-[120px] lg:gap-6">
            
            <div class="flex flex-col items-center p-4 gap-4 manga-r">
                <img src="../assets/imgs/Bulb.png" class="rounded-[50%] p-4 bg-[#e0e0ff]" alt="bulb icon">
                <div class="flex flex-col items-center py-2 px-4 gap-2 lg:">
                    <h3 class="text-[#171740] font-semibold text-2xl text-center">
                        Lorem, ipsum.
                    </h3>
                    <p class="font-normal text-lg text-[#242464] text-center">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
            </div>
            
            <div class="flex flex-col items-center p-4 gap-4 manga-r">
                <img src="../assets/imgs/Bulb.png" class="rounded-[50%] p-4 bg-[#e0e0ff]" alt="bulb icon">
                <div class="flex flex-col items-center py-2 px-4 gap-2 lg:">
                    <h3 class="text-[#171740] font-semibold text-2xl text-center">
                        Lorem, ipsum.
                    </h3>
                    <p class="font-normal text-lg text-[#242464] text-center">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
            </div>
            
            <div class="flex flex-col items-center p-4 gap-4 manga-r">
                <img src="../assets/imgs/Bulb.png" class="rounded-[50%] p-4 bg-[#e0e0ff]" alt="bulb icon">
                <div class="flex flex-col items-center py-2 px-4 gap-2 lg:">
                    <h3 class="text-[#171740] font-semibold text-2xl text-center">
                        Lorem, ipsum.
                    </h3>
                    <p class="font-normal text-lg text-[#242464] text-center">
                        Nam in velit malesuada, porta erat a, vestibulum orci. In ac nibh malesuada, volutpat metus ac, laoreet erat.
                    </p>
                </div>
            </div>

        </section>

        <section class="flex flex-col items-center py-8 px-4 lg:px-0 gap-6 w-full justify-center manga-d">

            <h2 class="font-semibold text-3xl text-[#171740]">
                Contact Us
            </h2>

            <form class="flex flex-col justify-center items-start p-6 gap-6 bg-[#242464] rounded-2xl lg:justify-between lg:py-10 lg:px-16 lg:items-center">
                
                <div class="flex flex-col items-center gap-4 flex-wrap lg:flex-row lg:flex-nowrap lg:justify-between w-full">
                   
                    <div class="flex flex-col items-start gap-1 w-full">
                        <label for="FirstName" class="text-lg text-white font-normal">
                            First Name
                        </label>
                        <input
                            type="text"
                            name="FirstName"
                            id="FirstName"
                            placeholder="Alex"
                            class="py-4 px-1 bg-[#fafaff] rounded-lg w-full">
                    </div>

                    <div class="flex flex-col items-start gap-1 w-full">
                        <label for="LastName" class="text-lg text-white font-normal">
                            Last Name
                        </label>
                        <input
                            type="text"
                            name="LastName"
                            id="LastName"
                            placeholder="Bloggs"
                            class="py-4 px-1 bg-[#fafaff] rounded-lg w-full">
                    </div>

                </div>

                <div class="flex flex-col items-start justify-start lg:items-start lg:justify-start w-full">
                    <label for="Email" class="text-lg text-white font-normal">
                        Email adress
                    </label>
                    <input
                        type="email"
                        name="Email"
                        id="Email"
                        placeholder="alex.blogs@email.com"
                        class="py-4 px-1 bg-[#fafaff] rounded-lg w-full">
                </div>

                <div class="flex flex-row items-center gap-4 w-full flex-wrap lg:justify-start">

                    <label for="message" class="text-lg text-white font-normal">
                        Your message
                    </label>
                    <textarea
                        name="message"
                        id="message"
                        cols="30"
                        rows="10"
                        placeholder="Please enter your message"
                        class="py-4 px-1 bg-[#fafaff] rounded-lg w-full h-1/4"
                    >
                    </textarea>

                    
                </div>
                <button class="w-full lg:w-2/4 bg-[#5555ff] py-3 px-8 font-semibold text-white hover:bg-[#FCAF3B] rounded-lg duration-300">
                    Submit message
                </button>

            </form>

        </section>

    </main>

    <footer class=" flex flex-col items-start justify-center py-8 px-4 gap-6 bg-[#242464] lg:flex-row md:py-16 md:px-24 md:gap-8 md:justify-between">
        <div class="flex flex-col items-start gap-6 md">
            <img src="../assets/imgs/logo2.png" class=" w-28" alt="logo image">
            <div class="flex flex-row items-start gap-4">
                
                <a href="#">
                    <img src="../assets/imgs/Facebook.png"  alt="facebook logo">
                </a>

                <a href="#">
                    <img src="../assets/imgs/Instagram.png" alt="intsagram logo">
                </a>
                
                <a href="#">
                    <img src="../assets/imgs/Twitter.png"   alt="twitter logo">
                </a>

                <a href="#">
                <img src="../assets/imgs/YouTube.png"   alt="youtube logo">
                </a>

            </div>
        </div>

        <div class="flex flex-col items-start gap-2">
            <a href="#" class="text-white text-lg font-semibold">Company</a>
            <a href="#" class="text-white text-lg">About us</a>
            <a href="#" class="text-white text-lg">Meet the team</a>
            <a href="#" class="text-white text-lg">Careers</a>
            <a href="#" class="text-white text-lg">Blog</a>
        </div>

        <div class="flex flex-col items-start gap-2">
            <a href="#" class="text-white text-lg font-semibold">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
        </div>

        <div class="flex flex-col items-start gap-2">
            <a href="#" class="text-white text-lg font-semibold">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
            <a href="#" class="text-white text-lg">Product</a>
        </div>

        <div class="flex flex-col justify-center items-center w-full gap-4 lg:w-1/5 lg:flex-row">
            <button class="flex flex-row justify-center items-center bg-[#fafaff] py-2 text-center w-full rounded-lg hover:bg-[#FCAF3B] duration-300">
                <img src="../assets/imgs/Apple_App_Store.png" alt="app store logo">
                <p class="text-lg font-semibold text-black">App Store</p>
            </button>

            <button class="flex flex-row items-center justify-center bg-white w-full rounded-lg py-2 hover:bg-[#FCAF3B] duration-300">
                <img src="../assets/imgs/Google_Play.png" alt="app store logo">
                <p class="text-lg font-semibold text-black">Play Store</p>
            </button>
        </div>
        
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

    const hiddenElementsRight = document.querySelectorAll('.manga-r')
    hiddenElementsRight.forEach((el) => observer.observe(el))
    const hiddenElementsleft = document.querySelectorAll('.manga-r')
    hiddenElementsleft.forEach((el) => observer.observe(el))
    const hiddenElementsUp = document.querySelectorAll('.manga-p')
    hiddenElementsUp.forEach((el) => observer.observe(el))
    const hiddenElementsDown = document.querySelectorAll('.manga-d')
    hiddenElementsDown.forEach((el) => observer.observe(el))
    // const hiddenElementsDown = document.querySelectorAll('.manga-d')
    // hiddenElementsDown.forEach((el) => observer.observe(el))
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

.manga-r {
    opacity: 0;
    transition: all 1s;
    transform: translateX(-100%);
    filter: blur(2px);
}
.manga-p {
    opacity: 0;
    transition: all 1s;
    transform: translateY(-100%);
    filter: blur(2px);
}
.manga-d {
    opacity: 0;
    transition: all 1s;
    transform: translateX(100%);
    filter: blur(2px);
}
.manga-r:hover button {
    background-color: #FCAF3B;
    transition-delay: inherit;
}
.manga-l {
    opacity: 0;
    transition: all 1s;
    transform: translateX(100%);
    filter: blur(2px);
}
.manga-l:hover button {
    background-color: #FFF;
}
.show {
    opacity: 1;
    filter: blur(0px);
    transform: translateX(0);
}

.manga-r:nth-child(2){
    transition-delay: 200ms;
}
.manga-r:nth-child(3){
    transition-delay: 400ms;
}
.manga-l:nth-child(2){
    transition-delay: 200ms;
}
.manga-l:nth-child(3){
    transition-delay: 400ms;
}
input::placeholder ,textarea::placeholder {
    font-weight: 400;
    font-size: 18px;
    color: #5d5dc5;
}
</style>
