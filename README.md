@use "../../../assets/styles/config/colours.scss" as *;

.sticky-bar{
    &-container{
    position: relative;
    backdrop-filter: blur(12px) saturate(180%);
    -webkit-backdrop-filter: blur(12px) saturate(180%);
    background-color: $yellow;
    box-shadow: 0 4px 30px rgba(0,0,0,0.1);
    color: $black;
    font-weight: bold;
    margin-top: 0 !important;
    z-index: -3;
    overflow: hidden;
    animation: sticky-bar-animate-background 0.8s ease-in-out 1.6s forwards;
    opacity: 0;
    visibility: hidden;
    &.z-top{
        z-index: 500 !important;
    }

    will-change: transform;
    transition: transform 0.8s ease-in-out 0s, opacity 0.4s ease-in-out;
    transform: translateY(-100%);
    &.active{
        opacity: 1;
        transform: translateY(0);
        visibility: visible;
    }
}
    &-content{
        background-color: transparent;
        gap: 1rem;
        padding: 0.6rem 1rem;
        display: flex;
        align-items: center;
        justify-content: center;
        @media only screen and (max-width: 600px){
            flex-wrap: wrap;
        }
    }
    &-message{
        margin-top: 1rem;
        margin-bottom: 1rem;
    }
    &-cta{
        margin-bottom: 0px;
        .uod-icons{
            margin-top:-2px;
        }
    }
    
}


@keyframes sticky-bar-animate-background{
    0%{
        background-color: $yellow;
    }100%{
        background-color: rgba(250, 250, 252, 0.8);
    }
}

.center-align > .sticky-bar-container {
    margin-left: -1rem;
    margin-right: -1rem;

    @media only screen and (min-width: 768px){
        margin-left: -40px;
        margin-right: -40px;
    }
    
}



<div id="header" align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzFmNTIwZDllYzNiZDY0M2NmMmRkYjIzYzM0YjhjZmE0N2JlNDg2YyZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PXM/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100">
</div>
<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/michael-okolo-b50898266/">
  <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="#">
  <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="#">
  <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=michaelokolo&style=flat-square&color=blue" alt="" />
</p>
<p align="center">
  Hi 👋, I'm Michael Okolo
</p>

<hr>
<div align="center">
  <img src="https://github.com/michaelokolo/michaelokolo/assets/91018269/2cefb90b-8407-48e6-8d21-61312a0b06ae" width="400">
</div>
<p align="center">A Software Engineer</p>

### :man_technologist: About Me:
I am a dedicated self-taught React and .NET Developer who specializes in full stack web development. I love coming up with ideas for software and turning them into beautiful user interfaces. I pay close attention to the user experience, architectural design, and code quality of the things I create. I love connecting with new people, give a shout at <a href="mailto:michaelokolo62@yahaoo.com">michaelokolo62@yahoo.com</a>
<hr>


### :hammer_and_wrench: Languages and tools:<br>
<img src="https://skills.thijs.gg/icons?i=react,html,javascript,github,css,bootstrap,express,nodejs,jquery&theme=light" width="500"/>
<hr>
- :mailbox: How to reach me: <a href="mailto:michaelokolo62@yahoo.com">michaelokolo62@yahoo.com</a><br>
- :zap: Fun fact: I love playing ⚽ & 🎸
<hr>


### :fire: My Stats:<br><br>
<img src="http://github-readme-streak-stats.herokuapp.com?user=michaelokolo&theme=dark&hide_border=true"/>
<br>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=michaelokolo&layout=compact&theme=vision-friendly-dark"/>

