<template>

    <header class="flex flex-row items-center justify-between w-full px-12 pt-4 text-gray-600">
        <div class="flex flex-row items-end justify-center">
            <a href="#" class="text-gray-700 font-bold flex flex-row text-5xl mr-5">
            <img src="../assets/imgs/logo.png" class=" w-28" alt="logo images">
            </a>
            <div class="here max-md:hidden">
                <a href="#" class="mx-4 text-lg text-[#242464]">About us</a>
                <a href="#" class="mx-4 text-lg text-[#242464]">Download</a>
                <a href="#" class="text-lg text-[#242464]">Contact</a>
            </div> 
        </div>
        
        <div class="max-md:hidden">
            <a href="#" class="text-[#5555FF] text-lg">Log in</a>
            <a href="#" class=" bg-[#5555FF] text-white px-4 py-2 rounded-md text-center ml-4">Primary action</a>
        </div>
        <div class="links max-md:block hidden">
            <span id="menu" class=" w-5 h-[10px] cursor-pointer">
                <span class="bg-black h-[1px] mb-1"></span>
                <span class="bg-black h-[1px] mb-1"></span>
                <span class="bg-black h-[1px] mb-1"></span>
            </span>
            <ul>
                <li><a href="#" class="mx-4 text-lg text-[#242464]">About us</a></li>
                <li><a href="#" class="mx-4 text-lg text-[#242464]">Download</a></li>
                <li><a href="#" class="text-lg text-[#242464]">Contact</a></li>
            </ul>
        </div>


    </header>

    <main>

        <section>

        </section>
    
        <section>

        </section>
    
        <section>

        </section>
    
        <section>

        </section>
    
    </main>

    <footer>

    </footer>

</template>

<script setup>
const menu = document.getElementById("menu")



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
</style>