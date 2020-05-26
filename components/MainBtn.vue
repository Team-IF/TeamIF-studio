<template>
  <div>
    <nuxt-link to="/deeper-world" class="btn">
      <svg width="277" height="62">
        <defs>
          <linearGradient id="grad1">
            <stop offset="0%" stop-color="#FF8282" />
            <stop offset="100%" stop-color="#E178ED" />
          </linearGradient>
        </defs>
        <rect
          x="5"
          y="5"
          rx="25"
          fill="none"
          stroke="url(#grad1)"
          width="266"
          height="50"
        ></rect>
      </svg>
      <!--<span>Voir mes réalisations</!-->
      <span>Deeper-World</span>
    </nuxt-link>
  </div>
</template>

<style scoped>
.container {
  height: 100%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.btn {
  margin-top: 10vh;
  position: relative;
  display: inline-block;
  width: 277px;
  height: 50px;
  font-size: 1em;
  font-weight: bold;
  line-height: 60px;
  text-align: center;
  text-transform: uppercase;
  background-color: transparent;
  cursor: pointer;
  text-decoration: none;
  font-family: 'Roboto', sans-serif;
  font-weight: 900;
  font-size: 17px;
  letter-spacing: 0.045em;
}

.btn svg {
  position: absolute;
  top: 0;
  left: 0;
}

.btn svg rect {
  stroke-width: 4;
  stroke-dasharray: 353, 0;
  stroke-dashoffset: 0;
  -webkit-transition: all 600ms ease;
  transition: all 600ms ease;
}

.btn span {
  background: rgb(255, 130, 130);
  background: -moz-linear-gradient(
    left,
    rgba(255, 130, 130, 1) 0%,
    rgba(225, 120, 237, 1) 100%
  );
  background: -webkit-linear-gradient(
    left,
    rgba(255, 130, 130, 1) 0%,
    rgba(225, 120, 237, 1) 100%
  );
  background: linear-gradient(
    to right,
    rgba(255, 130, 130, 1) 0%,
    rgba(225, 120, 237, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ff8282', endColorstr='#e178ed',GradientType=1 );

  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.btn:hover svg rect {
  stroke-width: 4;
  stroke-dasharray: 196, 543;
  stroke-dashoffset: 437;
}
</style>
