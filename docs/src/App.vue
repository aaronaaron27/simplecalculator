<template>
  <div id="app" margin-top="1">
    
    <div id="header">
        <div class='container'>Count, Count, Count ...</div>
    </div>
      <div class='container'>
        <div id="first">
          <br/><br/>

          <div><u><b>Developer:</b></u></div>
          <div><b style="color:violet;font-size:30px;">Aaron Nishanth</b></div><b/><b/>
          <img alt="Vue logo" src="./assets/nishanth.png" height="150">
            <br/><br/>
              <a href="https://br.linkedin.com/in/bnishanthreddy" target="new">linkedin profile</a>
        </div>
        <div id="second">
           <br/>
          <HelloWorld msg="Simple Calculator"/><br/>
          <div><b style="color:red;font-size:30px;">Simple Calculator</b> 
        </div>

         
        </div>

        
        </div>

        <div id="third">
       
         <div>
            <br><u><b>Features: </b></u><br/>
            <div>
            <i>
              <ul> 
                <li>Familiar UI</li> 
                <li>large numbers can be used</li> 
                <li>continuous logging
                 of all calculation stored</li> 
                 <li>Delete/Correct button</li>
                 <li>Autoplay of the calculation</li>
              </ul>
             </i>
             </div>
          </div>
       <br/><br/>
        </div>
      <div id="clear"></div>
    </div>
      </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#header {
    width: 100%;
    background-color: red;
    height: 30px;
}

#container {
    width: 300px;
    background-color: #ffcc33;
    margin: auto;
}
#first {
    margin-top: 50px;
    margin-left: 40px;
    width: 200px;
    float: left;
    height: 600px;
        background-color: GREY;
}
#second {
    margin-top: 50px;
    margin-left: 200px;
    width: 350px;
    float: left;
    height: 500px;
    background-color: green;
}

#third{
  margin-top: 50px;
    margin-left: 200px;
    margin-bottom: 50px;
    width: 350px;
    height: 600px;
    float: left;
    background-color: gold;
}
#clear {
    clear: both;
}


</style>
