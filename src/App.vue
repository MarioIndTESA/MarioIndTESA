<template>
  <router-view></router-view>
</template>

<script>
//import FormularioLogin from './components/FormularioLogin.vue'

export default {
  name: 'App'

}
</script>

<style>

html
{
    font-size: 62.5%;
    box-sizing: border-box;
}

*,*:before,*:after
{
    box-sizing: inherit;
    margin: 0;
}

body
{
    background-color: #011910;
    color: #d8d8d8;
    min-width: max-content;
    font-family: 'calibri';
    font-size: 16px;
    line-height: 1.8;
}
p{
    font-size: 2rem;
}
a
{
    text-decoration: none;
}
h1,h2,h3
{
    margin: 5rem / 2 0;
}

h1
{
    font-size: 3.8rem;
}
h2
{
    font-size: 3.4rem;
}
h3
{
    font-size: 3rem;
}
h4
{
    font-size: 2.6rem;
}
footer{
  margin-top: 2rem;
  background-color:#011910;
  width: 100%;
  color:#d8d8d8;
  padding: 2rem;
  text-align: center;
}

header {
  background-color: #037d50;
  padding: 1rem;
}


header h1 {
  height: max-content;
  width: max-content;
}

#app2
{
    background-color: #d8d8d8;
    color: #011910;
    padding: 2rem 0;
}







    .BotonPeligro {
  background-color: rgb(220, 82, 79);
  color: white;
  height: max-content;
  width: max-content;
  padding: 1rem;
  border-radius: 1rem;
  border-style: solid;
  border-color: black;
}

.BotonPeligro:hover {
  color: black;
  background-color: rgb(236, 159, 157);
}
  .Sombras
  {
      -webkit-box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.75);
      -moz-box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.75);
      box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.75);
  }
    .OpcionBoton {
    width: max-content;
    background-color: #037d50;
    padding: 1rem;
    border-style: solid;
    border-radius: 1rem;
    border-color: #011910;
    color: #d8d8d8;
  }
  
  .OpcionBoton:hover {
    background-color: #c0d6c0;
    color: #011910;
  }
  
  .nav-menu
  {
    background-color: #c0d6c0;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
  }
  .nav-menu a
  {
    font-size: 2rem;
    text-align: center;
    border-style: solid;
    border-width: .1rem;
    min-width: 10rem;
    border-color: #011910;
    color:#d8d8d8;
    background-color: #037d50;
    padding: 1rem;
  }

.background
{
  margin: auto;
  max-width: 105rem;
}
.bcD {
  background-color: #92bd8f;
  border-radius: 2rem;
  width: max-content;
  padding: 2rem;
}
</style>