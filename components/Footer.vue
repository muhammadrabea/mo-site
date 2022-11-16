<script>
export default {
    data()  {
        return {
            currentYear: new Date().getFullYear()
        }
    }
}
</script>

<template>
    <div class="flex flex-wrap flex-col justify-evenly items-center font-bold box-content mt-10 h-20 pt-4 w-full text-white bg-[#66BFBF]">
     <ul class="style-none flex justify-center items-center">
        <li><a href="https://www.linkedin.com/in/muhammad-rashwan-3583991ab">LinkedIn</a></li>
        <li><a href="https://twitter.com/_RashwanZzz?t=ANuEHiecskU54B_1wqDw4Q&s=09">Twitter</a></li>
        <li><a href="https://www.facebook.com/profile.php?id=100006441699951">Facebook</a></li>
        <li><a href="https://instagram.com/muhammadrashwan_?igshid=YmMyMTA2M2Y=">Instagram</a></li>
      </ul>
       <p>© {{currentYear}} Muhammad Rashwan @ IEEE ASB</p>
    </div>  
    
  </template>
  
  <style scoped>
   ul li {
     margin: 0 10px;
   }
  a {
    color:#11999E;
    text-decoration: none;
  }
  </style>