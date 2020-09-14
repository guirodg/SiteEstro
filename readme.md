- {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Architects Daughter', cursive;
  }

body {
width: 100%;
height: 100vh;

    background-color: #1a1a1a;

}

header {
width: 100%;
height: 70px;

background-color: #101010;

box-shadow: 0px 5px 20px #000;

padding: 10px;

display: flex;
align-items: center;

justify-content: space-between;
}

.menu {
list-style: none;

text-transform: uppercase;

display: flex;
}

.menu li a {
color: #fff;

display: block;
text-decoration: none;

padding: 10px 20px 10px 20px;

border-radius: 10px;

margin-left: 10px;

display: inline-block;
-webkit-transform: perspective(1px) translateZ(0);
transform: perspective(1px) translateZ(0);
box-shadow: 0 0 1px rgba(0, 0, 0, 0);
position: relative;
overflow: hidden;
}

.menu li a:before {
content: "";
position: absolute;
z-index: -1;
left: 0;
right: 100%;
bottom: 0;
background: #ee6781;
height: 4px;
-webkit-transition-property: right;
transition-property: right;
-webkit-transition-duration: 0.3s;
transition-duration: 0.3s;
-webkit-transition-timing-function: ease-out;
transition-timing-function: ease-out;
}

.menu li a:hover:before, .menu li a:focus:before, .menu li a:active:before {
right: 0;
}

.logo {
width: 45px;
height: 45px;

border-radius: 10px;

}

h1 {
color: #FFF;
text-align: center;

margin-top: 20px;
}

p {
color: #FFF;
text-align: center;

margin-top: 20px;
}

.container {
max-width: 1200px;
margin: 0 auto;

display: flex;

flex-wrap: wrap;
}

.container div {
flex: 1 1 300;

margin: 10px;
}

img {
width: 100%;
border-radius: 10px;
}

.logopg img {
height: 50px;
color: #FFF;
}

.main {
display: grid;
grid-template-columns: 1fr 1fr;
}

.main .text {
border: 1px solid #ee6781;
margin: 15px;
display: block;
}

.main .text p {
margin: 15px;
}

.main .container {
display: block;
}

    width: 100%;
    height: 70vh;
    background-image: url('https://s3.amazonaws.com/nikeinc/assets/93394/NikeNews_SP20_BB_Nike_Adapt_BB_2.0_Primary_Hero_Square_01_native_1600.jpg?1579111067');

    background-size: cover;
    background-position: center;
    background-attachment: fixed;

}
