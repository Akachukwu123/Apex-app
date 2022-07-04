<template>
 
 <div class="body-main">
  <!--navbar codes begins here-->
<nav class="bg-white md:px-14 px-5 sm:px-4 py-2.5">
  <div class="container flex flex-wrap justify-between items-center mx-auto">
  <a href=" " class="flex items-center">
      <img src="./assets/logo.png" class="mr-3 h-6 sm:h-9" /> 
  </a>
  <div class="flex md:order-2">
      <div class="hidden justify-between items-center w-full md:flex md:w-auto" id=" ">
        <ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
          <a href="#" class="log md:hover:text-orange-500" aria-current="page" style="margin-top:10px;">Login</a> 
          <button type="button" class="text-white bg-orange-400 focus:ring-4 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0">Get Started Free</button>
        </ul>
      </div>
      <button id="mybutton" data-collapse-toggle="mobile-menu-4" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="mobile-menu-4" aria-expanded="false">
      
      <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
    </button>
  </div>
  <div class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1" id="mobile-menu-4">
    <ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
      <li>
        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Demos</a>
      </li>
      <li>
        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
      </li>
      <li>
        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Blog</a>
      </li>
      <li>
        <a href="#" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Pages</a>
      </li>
      <li>
        <a href="#" class="block py-2 mb-4 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Contact</a>
      </li>
      <li>
        <a href="#" class="hide block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-orange-400 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Login</a>
      </li>
      <li>
        <button type="button" class="hide text-white bg-orange-400 focus:ring-4 font-medium rounded-md text-sm px-5 py-2.5 text-center mt-2 mr-3 md:mr-0">Get Started Free</button>
      </li>
    </ul>
  </div>
  </div>
</nav>
 <!-- navbar codes ends here-->



 <!-- Landing page codes begins here-->
<div class="md:px-14 px-5 sm:grid grid-cols-2 gap-2 mx-auto py-5 ">
        <div class="sm:pt-0">
           <h1 class="md:text-6xl font-bold text-4xl md:mt-12 mt-10">
            Start chatting with customers, anytime, anywhere with Apex
           </h1> 
           <p class="text-2xl text-gray-700 mt-7 mb-7 w-11/12"> 
            Great software that allows you to chat from any place at any time without any interruption. 
            </p>
             <!-- landing page button -->
            <a href="" class="text-white bg-orange-500 font-medium rounded-lg text-sm px-5 py-2.5"> Start Chatting Now </a>
            
            <div class="sm:grid grid-cols-2 mt-14">
              <div>
                <img src="./assets/ellipse.png">
                <div class="float-right cust-info pr-4 md:-mt-16 -mt-14">
                  <li> <p class="text-2xl font-bold -mt-0.5">2,291</p> </li>
                  <li> <b class="font-normal text-gray-500">Happy Customers </b> </li>
                </div> 
              </div>  
              <div class="pl-4">
                <p class="text-2xl font-bold">4.8/5</p>
                <b class="font-normal -mt-0.5"> <font-awesome-icon icon="fa-solid fa-star" class="text-yellow-400" /> <font-awesome-icon icon="fa-solid fa-star" class="text-yellow-400" /> <font-awesome-icon icon="fa-solid fa-star" class="text-yellow-400" /> <font-awesome-icon icon="fa-solid fa-star" class="text-yellow-400" /> <font-awesome-icon icon="fa-solid fa-star" class="text-gray-400" /> </b>
                <b class="font-normal text-gray-500 -mt-0.5"> Rating </b>
              </div>  
            </div> 
        </div>
         
        <div class="h-14 dark:bg-gray-900 sm:items-center sm:pt-0">
          <img src="./assets/afro.png" class="md:mt-0 mt-12"> 
        </div>
  </div>
   <!-- Landing page codes ends here-->







 <!-- codes for the second Section after landing page begins here-->

 <div class="text-center md:mt-60 mt-96"> <h1 class="font-bold md:text-4xl text-3xl"> Features for a better experience </h1> </div>

 <div class="md:px-14 px-5 sm:grid grid-cols-3 gap-2 mx-auto py-5">
       <div class="bg-white">
          <div class="md:flex bg-white rounded-lg p-6">
            <img src="./assets/vido.png" class="h-8 w-8 md:h-10 md:w-10 rounded-full mx-auto md:mx-0">
            <div class="text-center md:text-left md:pl-4">
              <h3 class="text-lg font-bold">Video messaging</h3>
              <p class="text-gray-600 md:text-sm">This software is very easy for you to manage. You can use it as you wish</p>
            </div> 
          </div>
       </div> 
       <div class="bg-white">
          <div class="md:flex bg-white rounded-lg p-6">
            <img src="./assets/clock.png" class="h-8 w-8 md:h-10 md:w-10 rounded-full mx-auto md:mx-0">
            <div class="text-center md:text-left md:pl-4">
              <h3 class="text-lg font-bold">Save your time</h3>
              <p class="text-gray-600 md:text-sm">This software is very easy for you to manage. You can use it as you wish</p>
            </div> 
          </div>
       </div>  
       <div class="bg-white">
          <div class="md:flex bg-white rounded-lg p-6">
            <img src="./assets/network.png" class="h-8 w-8 md:h-10 md:w-10 rounded-full mx-auto md:mx-0">
            <div class="text-center md:text-left md:pl-4">
              <h3 class="text-lg font-bold">Keep safe & private</h3>
              <p class="text-gray-600 md:text-sm">This software is very easy for you to manage. You can use it as you wish</p>
            </div> 
          </div>
       </div> 
  </div>
   <!-- codes for the second Section after landing page begins here-->



  <!-- codes for the third Section begins here-->
  <div class="bg-gray-100 sm:grid grid-cols-2 gap-2 mx-auto md:p-24 p-10">
    <div class="sm:items-center">
        <img src="./assets/smile.png">
    </div>  
    <div class="text-left md:w-3/4">
        <h1 class="md:text-4xl text-3xl font-bold mt-4"> Meet your customers, with live video chat </h1>
        <p class="text-md mt-6"> Proin faucibus nibh et sagittis a. Lacinia purus ac amet pellentesque aliquam enim.</p>
        <p class="text-md mt-4"> Get paychecks up to two days early. Get a $20 bonus when you receive qualifying direct deposits </p>
    </div> 
  </div>
   <!-- codes for the third Section ends here-->





 <!-- codes for the fourth Section begins here-->
  <div class="md:px-28 px-5 sm:grid grid-cols-2 gap-2 mx-auto p-20">
    <div class="hide sm:items-center">
      <img src="./assets/hello.png">
    </div>  

    <div>
      <h1 class="md:text-4xl text-3xl font-bold mt-4 md:w-3/4"> Start selling directly inside conversations</h1>
      <p class="text-md mt-6 mb-7 md:w-4/5"> There are many variations of passages of Lorem Ipsum available, but the majority have suffered all injected humour or randomised words which don't look even slightly believable.  </p>
      <a href="" class="text-white bg-orange-400 font-medium rounded-lg text-sm px-5 py-2.5"> Start Chatting Now </a>
 
    </div>  

    <div class="responsive-hide sm:items-center">
      <img src="./assets/hello.png">
    </div> 
  </div>  
 <!-- codes for the fourth Section ends here-->




  <!-- codes for the fifth Section begins here-->
  <div class="bg-gray-100 sm:grid grid-cols-2 gap-2 mx-auto md:p-24 p-10">
    <div class="sm:items-center">
        <img src="./assets/inbox.png">
    </div>  
    <div class="text-left md:pl-10">
        <h1 class="md:text-4xl text-3xl font-bold mt-4 md:w-3/4"> Get direct orders from your customers</h1>
        <p class="text-md mt-6 md:w-4/5">  Create custom landing pages with Rareblocks that converts more visitors than any website. With lots of unique blocks easily build a page. There are many variations of passages of available. </p> 
        
        <div class="flex mt-8">
          <div class="flex"> 
            <h4 class="md:text-3xl text-2xl"> 4.3K+ </h4>
            <div><p class="text-sm">Websites</p>
            <p class="text-sm">Powering</p> </div>
          </div>

          <div class="flex pl-8"> 
            <h4 class="md:text-3xl text-2xl"> 7M+ </h4>
            <div><p class="text-sm">Chats in</p>
            <p class="text-sm">Last 2022</p> </div>
          </div>

        </div>
    </div> 
  </div>
   <!-- codes for the fifth Section ends here-->
 






  <div class="bg-orange-500 p-10">
    <div class="w-72 m-auto">
      <h1 class="text-3xl md:text-4xl text-white mt-10 text-center w-90">Our blessed client said about us 😍</h1>
    </div>
    <div class="sm:grid grid-cols-2 gap-2 mx-auto md:p-24 md:mt-0 mt-20">
      <div>
        <div class="bg-white rounded-lg p-5 px-10 text-center">
          <p class="text-2lg text-orange-500 font-bold"> "Incredible Experience"</p>
          <p class="text-gray-700 mt-5"> We had an incredible expereince working with Mixland and they were impressed they made such a big difference in only three weeks. Our team is grateful for the wonderful improvements they made and for their ability to get familiar with the concepts so quickly.  </p>
        </div>
        <div class="flex items-center ml-auto mr-auto mt-5 w-60">
          <img src="./assets/womanPhoto.png" class="rounded-full h-8 w-8 md:h-12 md:w-12">
          <div class="pl-5">
            <p class="font-bold text-2lg text-white"> Wade Warren </p>
            <p class="text-2lg text-white"> CEO, ABC Corporation</p>
          </div>
        </div> 
      </div>

      <div>
        <div class="bg-white rounded-lg p-5 px-10 md:mt-0 mt-10 text-center">
          <p class="text-2lg text-orange-500 font-bold"> "Dependable, Responsive, Professional"</p>
          <p class="text-gray-700 mt-5"> Fermin Apps has collaborated with Mixland team for several projects such as Photo Sharing Apps and Custom Social Networking Apps. The experience has been pleasant, professional and exceeding our expectations. The team is always thinking beyond.</p>
        </div>
        <div class="flex items-center ml-auto mr-auto mt-5 w-60">
          <img src="./assets/Photo.png" class="rounded-full h-8 w-8 md:h-12 md:w-12">
          <div class="pl-5">
            <p class="font-bold text-2lg text-white"> Esther Howard </p>
            <p class="text-2lg text-white"> CEO, ABC Corporation</p>
          </div>
        </div> 
      </div>  
    </div> 

  </div> 




  <!-- Codes for last section begins-->
  <div class="bg-white p-10">
    <div class="md:w-2/4 m-auto mb-8">
      <h1 class="text-3xl md:text-4xl text-black font-bold mt-10 text-center">Ready to grow your business? Start with Apex, become faster every second</h1>
    </div>
    
    <div class="text-center">
      <a href="" class="text-white bg-orange-500 font-medium rounded-lg text-sm px-5 py-2.5"> Start Chatting Now</a>
    </div>
  </div>

  <div class="sm:grid grid-cols-3 gap-2 mx-auto md:p-24 md:pb-3 md:mt-10 mt-20 pb-3 brands">
    <div class="items-center"> 
      <img src="./assets/logo.png" class="h-6 w-auto md:h-8 md:w-auto ml-auto mr-auto md:ml-0 md:mr-0">
    </div> 
    <div class="w-4/5 mr-auto ml-auto justify-between"> 
      <ul class="flex md:flex-row space-x-8 md:mt-0 mt-4 md:space-x-8 last-section">
        <li class="text-2lg">About</li>
        <li class="text-2lg">Features</li>
        <li class="text-2lg">Works</li>
        <li class="text-2lg">Support</li>
      </ul>  
    </div>  
    <div class="mr-auto ml-auto md:w-6/12 w-4/12 md:mt-0 mt-4"> 
      <div class="md:float-right">
          <font-awesome-icon icon="fa-brands fa-twitter" class="text-orange-500" />
        <font-awesome-icon icon="fa-brands fa-facebook-f" class="text-orange-500 ml-3" />
        <font-awesome-icon icon="fa-brands fa-instagram" class="text-orange-500 ml-3" />
        <font-awesome-icon icon="fa-brands fa-github" class="text-orange-500 ml-3" />
      </div> 
    </div> 
  </div> 

    <div class="sm:grid grid-cols-2  mx-auto pb-8 md:ml-20 md:mr-20 md:mt-10 mt-20">
      <div> 
      <p class="text-sm text-gray-400 md:text-left text-center md:mt-0 -mt-14"> © Copyright 2022, All Rights Reserved </p>
      </div>
      <div class="md:float-right text-center">
        <b class="md:float-right font-normal md:ml-5 text-sm text-gray-400"> Terms & Conditions </b> 
        <b class="md:float-right font-normal text-sm text-gray-400"> Privacy Policy </b>
      </div>
    </div>  
  <!-- Codes for last section ends -->
 </div>
</template>

<script> 
import './index.css';
import './main.js';

export default {
  name: 'App',
  components: { 
  }
}

window.addEventListener('DOMContentLoaded', function(){ 
  let doc = document.getElementById('mybutton');
  let list = document.getElementById('mobile-menu-4');
  doc.addEventListener('click', function(){
    let arr = Array.from(list.classList);
   if(arr.indexOf('hidden') > -1){ 
     let cl = arr.filter((l)=>l !='hidden');
    list.className = cl.join(" ");
   }else{
     arr.push('hidden');
     list.className = arr.join(" ");
   }
 })
 })
 
 
</script>

<style>  
.body-main{ 
  animation: glow 3s;
}

@keyframes glow {
  from{
    opacity: 0.1;
  }
  to{
    opacity: 1;
  }
}
.cust-info{  
  border-right: 1px solid black;
}
.cust-info li{
  list-style: none;
}  
.hide{
  display: none;
}
.brands{
  border-bottom: 1px solid gray;
}
@media screen and (max-width: 800px) {
  .cust-info{
    border-right: none;
  } 
  .hide{
    display: unset;
  }
  .responsive-hide{
    display: none;
  } 

}

</style>
