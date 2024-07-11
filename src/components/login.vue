<template>
  <div class="log-in">
    <div class="log-in-child" />
    <div class="log-in-item" />
    <div class="gittax-parent">
      <img class="group-child" alt="" src="@/assets/logo.png" />
      <div class="gittax">gittax</div>
      
    </div>
    <div class="div">........اللغة العربية</div>
  </div>
    <div class="group-parent">
      <div class="email-address-parent">
        <div class="email-address">email address</div>
        <div >
            <input type="text" class="group-item"  />
                
  
        </div>
      </div>
      <div class="password-parent">
    <div class="password">password</div>
    <div class="rectangle-wrapper">
      <div>
        <input type="password" class="group-inner" />
        <font-awesome-icon :icon="['fas', 'eye']" class="eye-icon" @click="togglePasswordVisibility" />
      </div>
    </div>
  </div>
        
      
      <div class="log-in1">log in</div>
      <div class="dont-have-an-container">
        <span>
          <span>don't have an account ?</span>
          <span class="span"> </span>
        </span>
        <span class="span">
          <span class="sign-up1">sign up </span>
        </span>
      </div>
      <div class="group-container">
        <div class="rectangle-container">
          <div class="rectangle-div" />
        </div>
        <div class="log-in2">log in</div>
      </div>
      <div class="group-div">
        <div class="rectangle-container">
          <div class="group-child1" />
        </div>
        <div class="log-in-with-google-parent">
          <div class="log-in-with">log in with google</div>
          <img class="google-1-icon" alt="" src="@/assets/google.png" />
        </div>
      </div>
      <div class="vuesaxlineararrow-left-parent">
        <img
          class="vuesaxlineararrow-left-icon"
          alt=""
          src="@/assets/arraw.png"
        />
        <div class="log-in-with">back to home page</div>
      </div>
      <div class="forget-password">forget password ?</div>
    </div>
  </template>
  <script>
    import { defineComponent } from "vue";
  
    export default defineComponent({
      name: "Group",
    });
  </script>
  <style >
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap");
body {
  margin: 0;
  line-height: normal;
}
:root {
  /* fonts */
  --font-poppins: Poppins;

  /* font sizes */
  --font-size-base: 1rem;
  --font-size-lg: 1.125rem;
  --font-size-7xl: 1.625rem;

  /* Colors */
  --color-white: #fff;
  --txt: #727272;
  --c6c6c: #6c6c6c;
  --color: #353535;
  --dfe0df-stroke: #dfe0df;
  --fedd59: #fedd59;
  --white: #fafafa;

  /* Border radiuses */
  --br-5xs: 8px;
}
.log-in-child {
    position: absolute;
    top: 0rem;
    left: 43.75rem;
    background-color: var(--color-white);
    width: 76.25rem;
    height: 64rem;
  }
  .log-in-item {
    position: absolute;
    top: 0rem;
    left: 0rem;
    background: linear-gradient(102.16deg, #303030, rgba(48, 48, 48, 0));
    width: 43.75rem;
    height: 64rem;
  }
  .gittax {
    position: absolute;
    top: 7.5rem;
    left: 0rem;
    text-transform: capitalize;
    font-weight: 500;
  }
  .group-child {
    position: absolute;
    top: 0rem;
    left: 0.188rem;
    width: 6.25rem;
    height: 6.25rem;
  }
  .gittax-parent {
    position: absolute;
    top: 26.563rem;
    left: 18.563rem;
    width: 6.688rem;
    height: 10.875rem;
  }
  .div {
    position: absolute;
    top: 1.875rem;
    left: 94.938rem;
    font-size: var(--font-size-lg);
    text-transform: capitalize;
    font-weight: 500;
    color: var(--color);
    text-align: center;
  }
  .log-in {
    width: 100%;
    position: relative;
    background-color: var(--color-white);
    height: 64rem;
    overflow: hidden;
    text-align: left;
    font-size: 2.25rem;
    color: var(--white);
    font-family: var(--font-poppins);
  }

    .email-address {
      position: absolute;
      top: 0rem;
      left: 0rem;
      text-transform: capitalize;
      font-weight: 500;
    }
    
    .group-item {
      position: absolute;
      top: 2.313rem;
      left: 0rem;
      border-radius: var(--br-5xs);
      border: 1px solid var(--dfe0df-stroke);
      box-sizing: border-box;
      width: 37.5rem;
      height: 3.125rem;
    }
    .email-address-parent {
      position: absolute;
      top: 6.438rem;
      left: 0rem;
      width: 37.5rem;
      height: 5.438rem;
    }
    .password {
      position: absolute;
      top: 0rem;
      left: 0rem;
      text-transform: capitalize;
      font-weight: 500;
      background: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), #353535;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .group-inner {
      position: absolute;
      top: 0rem;
      left: 0rem;
      border-radius: var(--br-5xs);
      border: 1px solid var(--dfe0df-stroke);
      box-sizing: border-box;
      width: 37.5rem;
      height: 3.125rem;}
    .rectangle-wrapper {
      position: absolute;
      top: 2.313rem;
      left: 0rem;
      width: 37.5rem;
      height: 3.125rem;
    }
    .vuesaxlineareye-icon1 {
      position: absolute;
      top: 3.125rem;
      left: 35.063rem;
      width: 1.5rem;
      height: 1.5rem;
    }
    .password-parent {
      position: absolute;
      top: 13.125rem;
      left: 0rem;
      width: 37.5rem;
      height: 5.438rem;
    }
    .log-in1 {
      position: absolute;
      top: 0rem;
      left: calc(50% - 300px);
      font-size: var(--font-size-7xl);
      text-transform: capitalize;
      font-weight: 600;
      text-align: left;
    }
    .span {
      color: var(--color);
    }
    .sign-up1 {
      text-decoration: underline;
      font-weight: 500;
    }
    .dont-have-an-container {
      position: absolute;
      top: 3.063rem;
      left: calc(50% - 300px);
      font-size: var(--font-size-base);
      text-transform: capitalize;
      text-align: left;
      color: var(--txt);
    }
    .rectangle-div {
      position: absolute;
      top: 0rem;
      left: 0rem;
      border-radius: var(--br-5xs);
      background-color: var(--fedd59);
      width: 37.5rem;
      height: 3.438rem;
    }
    .rectangle-container {
      position: absolute;
      top: 0rem;
      left: 0rem;
      width: 37.5rem;
      height: 3.438rem;
    }
    .log-in2 {
      position: absolute;
      top: 0.875rem;
      left: 17.125rem;
      text-transform: capitalize;
      font-weight: 500;
    }
    .group-container {
      position: absolute;
      top: 22.25rem;
      left: 0rem;
      width: 37.5rem;
      height: 3.438rem;
    }
    .group-child1 {
      position: absolute;
      top: 0rem;
      left: 0rem;
      border-radius: var(--br-5xs);
      border: 1px solid var(--dfe0df-stroke);
      box-sizing: border-box;
      width: 37.5rem;
      height: 3.438rem;
    }
    .log-in-with {
      position: absolute;
      top: 0rem;
      left: 2.125rem;
      text-transform: capitalize;
      font-weight: 500;
    }
    .google-1-icon {
      position: absolute;
      top: 0.125rem;
      left: 0rem;
      width: 1.5rem;
      height: 1.5rem;
      overflow: hidden;
    }
    .log-in-with-google-parent {
      position: absolute;
      top: 0.875rem;
      left: 11.938rem;
      width: 12.688rem;
      height: 1.688rem;
    }
    .group-div {
      position: absolute;
      top: 27.563rem;
      left: 0rem;
      width: 37.5rem;
      height: 3.438rem;
    }
    .vuesaxlineararrow-left-icon {
      position: absolute;
      top: 0.125rem;
      left: 0rem;
      width: 1.5rem;
      height: 1.5rem;
    }
    .vuesaxlineararrow-left-parent {
      position: absolute;
      top: 32.25rem;
      left: 12.063rem;
      width: 13.438rem;
      height: 1.688rem;
      color: var(--txt);
    }
    .forget-password {
      position: absolute;
      top: 19.5rem;
      left: 28.438rem;
      font-size: var(--font-size-base);
      text-decoration: underline;
      text-transform: capitalize;
      color: var(--c6c6c);
    }
    .group-parent {
      position: absolute;
      top: 15.063rem;
      left: 62.625rem;
      width: 37.5rem;
      height: 33.938rem;
      text-align: center;
      font-size: var(--font-size-lg);
      color: var(--color);
      font-family: var(--font-poppins);
    }
  </style>
  