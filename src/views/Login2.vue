<script setup>
import { onMounted } from 'vue';
import Parallax from 'parallax-js';

let parallaxInstance = null;

onMounted(() => {
  const sceneElement = document.getElementById('scene');
  if (sceneElement) {
    parallaxInstance = new Parallax(sceneElement, {
      relativeInput: true,
      clipRelativeInput: false,
      hoverOnly: false
    });
  }
});
</script>
<template>
  <div class="wrapper">
    <div class="top">
      <ul class="nav-wrapper">
        <li class="nav-item register-link">REGISTER</li>
        <li class="nav-item sign-in-link">SIGIN</li>
      </ul>
      <ul class="link-wrapper">
        <li class="link-item">
          <img src="@/assets/images/head-sculpture.jpg" alt="">
          <span>MAOS.</span>
        </li>
      </ul>
    </div>
    <div class="parallax-wrapper">
      <div id="scene">
        <div class="layer">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#010F1C" d="M-4283.3-877.2h9976v2610h-9976z" />
          </svg>
        </div>
        <div class="layer" data-depth="0.1">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#054B8C"
                  d="M-4283.3-877.2v2610h9976v-2610h-9976zM839.6 371c19.4 13.4 44.6 16.4 64.3 30.4 13.2 9.4 41.7 42.6 22.9 59.2 4.9-4.3 2.5-2.2 0 0l-.3.3c.1-.1.2-.2.3-.2-2.7 2.4-5.5 4.8-.3.2-18.9 16.1-39.5-6.5-54.1-16.9-23.1-16.5-48-26.3-75.2-33.6C740 395 680.7 397 622.1 396.2c-50.6-.7-112.8 9.6-152.1-30-10.9-11-25-30.5-12.6-45.5 19.8-24.3 47.3-4.6 68.5 3.8 20.9 8.3 39.7 5.4 63.4 7.2 9 .6 58.1-12.5 82.7-25 17.3-8.8 36.8-20.6 52.7-3.4 19.5 21 44.9 15.1 70.1 10.4 13.4-2.5 43-9.9 53.8 2.2 19.3 21.6-30.1 40.4-9 55.1zm-64.7 270.1c-7.3 19-69.3-26.7-78.6-31.7-20.4-10.9-42.1-18.6-63.9-26-5.3-1.8-64.9-20.4-47.5-32.9 31.6-22.6 97.2 8.7 127.3 21.3 23.8 10 77.7 30.4 62.7 69.3zm.6-1.5l-.1.2.1-.2zm-.2.5l-.3.7.3-.7zm325.3-485.7c-6.8 33.6-75.3 5.6-97.8 5.6-25 0-53.1 12-77.1-.3-16.5-8.4-27.7-48.4-.2-44.1 19 3 38.7 14.4 58.4 7.9 20.6-6.8 22.8-32.8 46.9-30.6 25.9 2.4 76.7 27.7 69.8 61.5z" />
          </svg>
        </div>
        <div class="layer" data-depth="0.4">
          <img class="Venus" src="@/assets/images/Venus.svg" alt="">
        </div>
        <div class="layer" data-depth="0.8">
          <img class="mercurio" src="@/assets/images/mercurio.svg" alt="">
        </div>
        <div class="layer" data-depth="0.2">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#0887CB"
                  d="M-4283.3-877.2v2610h9976v-2610h-9976zM917.2 396.1c19 10.6 72 85.5 21.8 87.9l10.9-.5-10.9.5c-15.5.7-8.2.4 0 0-55.1 2.6-111.8-42.3-164.4-56.1-70.2-18.4-144.7-12.8-216.5-16.1-48.7-2.2-128.4-3.9-122.1-73.9 2.1-23.6 20.5-45.4 43.8-50.9 24.8-5.8 40.4 18.5 60.8 27.3 21.7 9.3 53.2-2.1 76.2-3.2 32.5-1.6 59.2-26.2 89.9-34.7 21.8-6 39.7 12.4 58.8 19.2 25.4 9.1 53.3-.4 79.1-.5 34.9 0 19.8 37.2 19.4 57.9-.4 23.1 37 34 53.2 43.1zM791 672.9c-25.7-5.5-51.7-24.9-74.8-37.1-29.5-15.5-59.3-27.8-89.9-40.9-16.8-7.2-38.5-14.8-52-27.4-15.4-14.4-3.8-33.6 14.8-35.9 49.9-6 93.5 17.7 137.8 36 25.3 10.5 45.6 29 61.6 51 5.9 8.3 35.2 61.3 2.5 54.3zm325.1-512.1c-8.2 37-102.4 11.3-125.6 11.2-25.1-.2-51.1 7.8-75.4-2.3-23.4-9.7-26.1-36.1-10.3-55.6 14.5-17.9 39 5.7 57.7-2.1 20.9-8.7 31.4-31.1 55.5-32.5 21.2-1.3 45.4 10.8 62.8 24.3 15.5 12 39.7 37.1 35.3 57z" />
          </svg>
        </div>
        <div class="layer" data-depth="0.5">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#54C3FF"
                  d="M-4283.3-877.2v2610h9976v-2610h-9976zM982.9 483.9v-.2c.1.1.1.2 0 .2-5.2 19.4-2.3 8.6 0 0-10.9 39.9-80.8 25.4-108 15.6-64.9-23.3-123.8-54.5-193.4-63.1-39.9-4.9-80.3-7.3-120.5-9.6-32.6-1.9-68.4 3.9-100-5.4-63.8-19-34.6-89.1-21.1-133.4 31.7-37.2 111.8 13.8 146.7 13.1 33.3-.7 63.8-15.6 92.5-30.8 32.2-17.1 57.3 1.6 87.8 8.1 32.3 6.8 61.4 7.3 93.9 9.9 34.6 2.7 26.1 32.7 28.5 58 2.9 30.7 41.5 42.6 59.9 63.5 16.9 19.3 41.3 45.9 33.7 74 3.3-11.6 1.8-6.5 0 .1zM837.3 685.4c.1-.4.3-.8.5-1.4l-.5 1.4c0 .1-.1.3-.1.4l-.1.2.1-.2c-14.8 38.3-135-34.1-157-44.9-27.5-13.5-194-78.7-113-120.2 35.5-18.2 116 8.8 150.1 24.8 42.4 19.8 143.3 78.2 120 139.9zm2-5.2c.1-.2.1-.2 0 0zm0 .2l-.1.1.1-.1zm-.3.6l-.4 1 .4-1zm-.6 1.7l-.1.4.1-.4zm288-501.1l.2-.1s-.1.1-.2.1zm1.1-.5l.2-.1-.2.1zm.3-.2c.2 0 .2 0 0 0zm-2.9 1.4c-47.6 22.9-124.4 20.6-175.8 18.5-21.3-.9-51.8-7.9-68.2-22.6-24.3-21.8-.1-59.4 19.6-74.2 20-14.9 34.2-3.6 57-9.7 15-4 26.3-17.2 42.5-21.2 17.2-4.2 34.5-4.6 51.1 2.1 18.8 7.6 115.4 87.1 73.8 107.1z" />
          </svg>
        </div>
        <div class="layer" data-depth="0.6">
          <img class="Jupiter" src="@/assets/images/Jupiter.svg" alt="">
        </div>
        <div class="layer" data-depth="0.7">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#ADECFF"
                  d="M-4283.3-877.2v2610h9976v-2610h-9976zM962.3 544c6.9-1.7 11.5-2.8 0 0-35.2 8.5-71.1-4.2-103.8-16-41.5-15-83.7-28.4-126.1-40.6-80.6-23.1-158.9-28.5-241.1-40.1-37.6-5.3-124.6-6.9-130.6-56.2-4.4-35.5 19.9-62 42.3-86.1 10.1-10.9 16.5-19.9 21.4-33.7 5.9-16.6 30.4-15.4 45.3-16.4 35.1-2.4 63.7 11.7 97.5 15.5 38.6 4.4 77.1-9.7 114.9-15.5 34.8-5.3 68.8-5.9 102.9 3.9 34.9 10.1 74.8 9 107.6 25.5 25.5 12.9 37.6 52.6 55.7 74 26 30.8 52.2 60.3 71.5 96.1 11.2 20.7 30 55.2 4 72.5-18 11.8-41.2 12.2-61.5 17.1zM860.9 705.6c0-.1 0-.2.1-.3 0 .1 0 .2-.1.3 0 .2-.1.4-.1.6.1-.2.1-.4.1-.6-5.9 27.7-76.9 8.1-91.4 3.5-45.8-14.5-87.1-35.1-127.9-60.5-20.1-12.5-37.3-29-57.3-41.7-16.7-10.6-35.6-20.5-47.2-37.2-19.1-27.3 11.3-46.9 29.6-59.6 26.2-8.6 60.3 4.7 86.8 5.8 33.6 1.3 74.4 12.9 102.3 32.1 41.7 28.8 117.1 99.3 105.2 157.2.4-1.6.2-.9-.1.4zm-.2 1c-.5 2.6-.8 3.7-.8 4 .1-.4.5-2.4.8-4zm300.9-535.1c-12.5 53.9-151 44.7-189.9 44.5-61.8-.5-134.9-19.4-109.6-97.3 8.7-26.8 27.8-35.3 54.4-36.3 16.1-.6 27.7-6.1 40.6-15.1 17.8-12.5 37.9-9.6 58.6-8.5 29.5 1.5 73 22.9 91.5 47.3 9.5 12.5 16.2 26.5 30.4 34.7 11.7 6.6 27.9 13.7 24 30.7z" />
          </svg>
        </div>

        <div class="layer layer-mask" data-depth="0.9">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="-260.5 -143 1920 1080">
            <path fill="#FFF"
                  d="M-4283.3-877.2v2610h9976v-2610h-9976zM924.4 587c-76.3 35.7 33.1 149.2-60.1 163.3-79.8 12-168.9-13.7-235.3-56.9-37-24.1-70.5-52.9-106.5-78.4-37.3-26.4-28.7-42.7-23.9-83.1 8.5-71.1-124.9-50.8-167.4-87.9-32.8-28.6-13.7-75.7.6-109 12.9-30.1 21.1-69 40.4-95.5 21-28.8 58.5-20.3 89.4-20.5 46.8-.2 92.5 12.1 139.3 12.1 47.6 0 94-9.9 141.9-8.5 24 .7 83.6-3.6 102.1 15.5 5.2 12.8 57.3 18.8 68.5 23.4 30.5 12.7 53.2 36.3 73.8 61.5 33.9 41.5 111.8 107.8 108.8 167-4.9 96.6-112 69-171.6 97zm171.1-87.5v.1-.1zm1-18.8c0-.2 0-.2 0 0zm95.2-312.4c-2.9 60.4-113.6 61.2-153.3 64.4-67.9 5.4-150.5 10.8-201.8-42.4-19.3-20-19.8-52-12.2-77.2 10.3-33.8 34.9-44.5 67.7-48.4 32-3.9 59.5-23.8 89.9-26.8 36.3-3.6 68 6.7 97.6 25.1 12.1 7.5 38.1 39.5 57.8 57.5 17.1 15.5 55.7 18 54.3 47.8z" />
          </svg>
        </div>
        <div class="layer" data-depth="0.5">
          <img class="astronaut" src="../assets/images/astronaut.svg" alt="">
        </div>
      </div>
    </div>

  </div>
</template>

<style scoped>

* {
  padding: 0;
  margin: 0;
}



.wrapper {
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  width: 100vw;
  height: 100vh;
  background-color: #fff;
  padding: 30px;
  overflow: hidden;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

.wrapper .top {
  width: 100%;
  height: 50px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  font-weight: 900;
  font-size: 25px;
}

.wrapper .top ul {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.wrapper .top ul li {
  margin: 0 35px;
  cursor: pointer;
  -webkit-transition: .5s;
  transition: .5s;
}

.wrapper .top ul li:hover {
  color: #4eaaff;
}

.wrapper .top .nav-wrapper .sign-in-link {
  color: #4eaaff;
}

.wrapper .top .link-wrapper .link-item {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  margin-right: 10px;
  z-index: 1;
}

.wrapper .top .link-wrapper .link-item img {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  margin-right: 20px;
}

.wrapper .top .link-wrapper .link-item span {
  font-size: 30px;
  font-weight: 900;
}



.wrapper .parallax-wrapper {
  width: 100vw;
  height: 100%;
}

.wrapper .parallax-wrapper #scene {
  position: relative;
  left: -15%;
  overflow: hidden;
  height: 100%;
  width: 100%;
}

.wrapper .parallax-wrapper #scene .layer {
  position: absolute;
  top: 0%;
  left: 0%;
  width: 100%;
  height: 100%;
}

.wrapper .parallax-wrapper #scene .layer svg {
  position: absolute;
  width: 99%;
  height: 99%;
  left: 0;
  top: 0;
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
  -webkit-filter: drop-shadow(5px 5px 5px rgba(0, 0, 0, 0.3));
  filter: drop-shadow(5px 5px 5px rgba(0, 0, 0, 0.3));
}

.wrapper .parallax-wrapper #scene .layer svg::before {
  content: "";
  display: block;
  height: 110%;
  /* 调整为您需要的宽度 */
  border-right: 80px solid #FFF;
  /* 创建L型的左下部分 */
  position: absolute;
  top: -5%;
  right: -125px;
}

.wrapper .parallax-wrapper #scene .layer .mercurio {
  position: absolute;
  left: 45%;
  top: 68%;
}

.wrapper .parallax-wrapper #scene .layer .Jupiter {
  position: absolute;
  left: 32%;
  top: 40%;
}

.wrapper .parallax-wrapper #scene .layer .Venus {
  position: absolute;
  left: 63%;
  top: 18%;
}

.wrapper .parallax-wrapper #scene .layer .astronaut {
  width: 800px;
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.wrapper .parallax-wrapper #scene .layer-mask::before {
  content: "";
  display: block;
  width: 125%;
  height: 125%;
  position: fixed !important;
  left: -10% !important;
  top: -15% !important;
  z-index: 1;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#fff), color-stop(4%, #fff), color-stop(4%, transparent), color-stop(95%, transparent), color-stop(95%, #fff), to(#fff)), -webkit-gradient(linear, left top, right top, from(#fff), color-stop(15%, #fff), color-stop(15%, transparent), color-stop(88%, transparent), color-stop(88%, #fff), to(#fff)), -webkit-gradient(linear, left top, left bottom, from(#fff), color-stop(15%, #fff), color-stop(15%, transparent), color-stop(88%, transparent), color-stop(88%, #fff), to(#fff));
  background-image: linear-gradient(#fff, #fff 4%, transparent 4%, transparent 95%, #fff 95%, #fff 100%), linear-gradient(to right, #fff, #fff 15%, transparent 15%, transparent 88%, #fff 88%, #fff 100%), linear-gradient(to bottom, #fff, #fff 15%, transparent 15%, transparent 88%, #fff 88%, #fff 100%);
}

@-webkit-keyframes jello-horizontal {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
    transform: scale3d(1.25, 0.75, 1);
  }
  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
    transform: scale3d(0.75, 1.25, 1);
  }
  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
    transform: scale3d(1.15, 0.85, 1);
  }
  65% {
    -webkit-transform: scale3d(0.95, 1.05, 1);
    transform: scale3d(0.95, 1.05, 1);
  }
  75% {
    -webkit-transform: scale3d(1.05, 0.95, 1);
    transform: scale3d(1.05, 0.95, 1);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes jello-horizontal {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
    transform: scale3d(1.25, 0.75, 1);
  }
  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
    transform: scale3d(0.75, 1.25, 1);
  }
  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
    transform: scale3d(1.15, 0.85, 1);
  }
  65% {
    -webkit-transform: scale3d(0.95, 1.05, 1);
    transform: scale3d(0.95, 1.05, 1);
  }
  75% {
    -webkit-transform: scale3d(1.05, 0.95, 1);
    transform: scale3d(1.05, 0.95, 1);
  }
  100% {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@media screen and (max-width: 992px) {
  .wrapper .top {
    width: 100%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    position: relative;
    z-index: 2;
  }
  .wrapper .top .nav-wrapper {
    width: 100%;
    list-style: none;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .wrapper .top .nav-wrapper .nav-item {
    margin: 0 15px;
    text-align: center;
    font-size: 1rem;
  }
  .wrapper .top .link-wrapper {
    display: none;
  }
  .wrapper .parallax-wrapper {
    position: absolute;
    left: 50%;
    top: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    background: url("@/assets/images/astronaut.svg");
    background-size: cover;
  }
  .wrapper .parallax-wrapper #scene {
    display: none;
  }


}

</style>