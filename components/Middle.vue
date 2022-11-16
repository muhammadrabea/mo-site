<template>
    <div class="font-sans flex flex-wrap flex-col justify-center items-center p-10 base font-medium">
        <img class="w-40 h-44 rounded-full box-border" src="../Public/Profile.jpg" alt="Muhammad's Profile picture">
      <h2 class=" text-3xl pt-5">Hello.</h2>
      <p class="py-10 w-1/3 text-center">
        I am a Front-End Web Developer.
        I'm a volunteer in IEEE Aswan 
        Student Branch and I 'love' Lattes and 
        singing all day long.
    </p>
    <span>.....</span>
    <h2 class="text-3xl">My Skills.</h2>
    
    <section>
        <img class="w-32 h-32 rounded-full" src="../Public/tag.png" alt="Muhammad's Profile picture">
        <article class="pl-10 w-3/6">
            <h3>Design & Development</h3>
            <p>I started to Learn Coding when I was 20 years old
                because I wanted to make money and be financially
                independent. I managed to finish the whole Web development 
                course provided from FWD initiative & Udacity. Right now,
                I have finished a lot of projects and practiced 
                a lot on my programming skills, my problem solving
                and being more creative. 
            </p>
        </article>
    </section>
    <section>
        <article class="w-3/6">
            <h3>Music Geek</h3>
            <p>
                My best skill would actually be discovering music.
                I have 7 playlists on spotify with a total of 3k songs.
                They are a mix of differnet songs from all around the world.
                I do enjoy discovering new artists and well composed music.
                I have been doing that since the age of 10 So, I definetly 
                know the difference between the well composed one and the 
                normal average song that you can hear, here and there.
            </p>
        </article>
        <img class="w-36 h-36 rounded-full" src="../Public/headphone.jpeg" alt="Muhammad's Profile picture">
      </section>
      <span>.....</span>
      <section class="font-sans flex flex-wrap flex-col justify-center items-center p-10 base font-medium">
        <h2 class="text-3xl pt-5">Get In Touch</h2>
        <h3 class="py-10">If you love music as much as I do</h3>
        <p class="w-1/3 text-center">
          Enjoying music that much? Why don't you slide up and share some ?
          We can code along exchanging those good loud vibes !
          "Or quiet, who knows?"
        </p>
      </section>
      <a href="https://wa.me/201552497677" class="btn">
        CONTACT ME
      </a>
    </div>
  </template>
  
  <style scoped>
  
  span {
    color: #a8a8a8;
    font-size: 2em;
    letter-spacing: 5px;
    font-weight: bold;
  }
  section {
    display: flex;
    justify-content: center;
    align-items: left;
    width: 100%;
    text-align: left;
    margin: 15px 0;
  }

  
  h2 {
    font-weight: 600;
    color:#66BFBF;
    letter-spacing: 1px;
  }
  h3 {
    font-weight: bold;
    color:#11999E;
  }
  .btn {
     font-family: Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
      Cantarell, 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
    color: white;
    width:130px;
    height: 35px;
    font-weight: bold;
    background: #11999E;
    border-style: none;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px #66BFBF;
    margin-top: 20px;
    display: flex;
    justify-content: center;
    align-items: center;  
}
  
  button:hover {
    cursor: pointer;
  }
  </style>
  