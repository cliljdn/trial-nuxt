<template>
  <div class="pb-11 lg:pb-56" id="Hero-Ellipse">
    <div
      id="Hero-Title"
      class="text-center pt-11 px-11 lg:pt-36 md:pt-36 lg:px-40 md:px-40"
    >
      <p id="Hero-Ellipse-Right" class="md:text-5xl font-bold text-white">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit dolor
      </p>
      <span class="font-size-span mt-11 mb-11 md:px-60 lg:px-60 text-gray-400"
        >Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur.</span
      >
      <div class="mt-5">
        <a
          href="#"
          class="
            bg-blue-custom
            text-white
            font-bold
            p-4
            text-xs
            p-4
            rounded-xl
            lg:text-lg
            md:text-lg md:leading-5
            lg:leading-5
          "
          >Book Now</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
.font-size-heading {
  font-size: 48px !important;
  line-height: 56.25px !important;
}
.font-size-span {
  font-size: 24px !important;
  line-height: 28.13px !important;
  font-weight: 400;
  text-align: center;
}
.bg-ShadeGray {
  background-color: #232323;
}
.bg-blue-custom {
  background-color: #4ba9dc;
}
.bg-blue-custom:hover {
  background-color: #7ed0fd;
}
#Hero-Title::after {
  content: "";
  position: absolute;
  width: 751.6px;
  height: 751.6px;
  left: -464px;
  top: 130px;
  opacity: 0.5;
  z-index: -1;
  background: radial-gradient(
    50% 50% at 50% 50%,
    #df3832 0%,
    rgba(223, 56, 50, 0) 100%
  );
}
#Hero-Title::before {
  content: "";
  position: absolute;
  width: 751.6px;
  height: 751.6px;
  left: 922.05px;
  top: -112.67px;
  opacity: 0.5;
  z-index: -1;
  background: radial-gradient(
    50% 50% at 50% 50%,
    #df3832 0%,
    rgba(223, 56, 50, 0) 100%
  );
}
#Hero-Ellipse::before {
  content: "";
  position: absolute;
  width: 423.68px;
  height: 844.93px;
  left: -107.2px;
  top: -201.22px;
  z-index: -1;
  opacity: 0.5;
  border: 1px solid #4ba9dc;
  box-sizing: border-box;
  border-radius: 50%;
  transform: matrix(0.55, 0.87, -0.8, 0.56, 0, 0);
}
#Hero-Ellipse::after {
  content: "";
  position: absolute;
  width: 417.62px;
  height: 821.32px;
  left: -139.33px;
  z-index: -1;
  top: -208px;
  border-radius: 50%;
  opacity: 0.5;
  border: 1px solid #4ba9dc;
  box-sizing: border-box;
  transform: matrix(0.55, 0.87, -0.8, 0.56, 0, 0);
}
#Hero-Ellipse-Right::before {
  content: "";
  position: absolute;
  width: 423.68px;
  height: 844.93px;
  left: 1083.78px;
  top: -61.12px;
  opacity: 0.5;
  z-index: -1;
  border-radius: 50%;
  border: 1px solid #df3832;
  box-sizing: border-box;
  transform: matrix(0.83, -0.52, 0.59, 0.84, 0, 0);
}
#Hero-Ellipse-Right::after {
  content: "";
  position: absolute;
  width: 417.62px;
  height: 821.32px;
  z-index: -1;
  left: 1060.17px;
  top: -28.19px;
  border-radius: 50%;
  opacity: 0.5;
  border: 1px solid #df3832;
  box-sizing: border-box;
  transform: matrix(0.83, -0.52, 0.59, 0.84, 0, 0);
}
@media only screen and (min-width: 320px) and (max-width: 767px) {
  #Hero-Title::after {
    display: none;
  }
  #Hero-Title::before {
    display: none;
  }
  #Hero-Ellipse::before {
    display: none;
  }
  #Hero-Ellipse::after {
    display: none;
  }
  #Hero-Ellipse-Right::before {
    display: none;
  }
  #Hero-Ellipse-Right::after {
    display: none;
  }
  .font-size-heading {
    font-size: 20px !important;
    line-height: 1.5em !important;
  }
  .font-size-span {
    font-size: 12px !important;
    line-height: 1em !important;
    font-weight: 400;
    text-align: center;
  }
}
</style>
