<template>
  <div class="bg-img">
      <div class='content font-mono italic text-center flex flex-col justify-top items-center w-full h-[450px] '>
          <section>
              <h1 class="text-6xl text-500 text-white">I'm Muhammad</h1>
              <h2 class="text-2xl text-500 text-white">
                  A Web Developer.
                </h2>
            </section></div>
        </div>
</template>

<style scoped>
div {
    position:relative;
}

.bg-img {
    background-image: url(../Public/wp7664856.webp);
    background-repeat: no-repeat;
    background-size:cover;
    background-position:center;
}
@media screen and (max-width: 1024px) {
    div {
        height:200px;
    }
}
@media screen and (max-width: 1024px) {
    h1 {
        font-size: 1.6rem;
    }
    h2 {
        font-size: 1.2rem;
    }
}
@media screen and (min-width: 1024px) {
    .content::before {
        width:15%;
        height:15%;
    }
}
@media screen and (max-width: 1000px) {
    .content::before {
        width:7%;
        height:4%;
    }
}
@media screen and (max-width: 1000px) {
    .content::after {
        width:7%;
        height:4%;
    }
}
@media screen and (min-width: 1024px) {
    .content::after {
        width:15%;
        height:15%;
    }
}
.content::before {
    position: relative;
    content: '';
    display: inline-block;
    width: 15%;
    height: 15%;
    background:url(../Public/Cloud2.png);
    background-repeat: no-repeat;
    background-size: 100% 100%;
    top: 50%;
    left: -35%;
}

.content::after {
    position: relative;
    content: '';
    display: inline-block;
    width: 15%;
    height: 15%;
    background:url(../Public/Cloud2.png);
    background-repeat: no-repeat;
    background-size: 100% 100%;
    bottom: 20%;
    left: 40%;
}

</style>
