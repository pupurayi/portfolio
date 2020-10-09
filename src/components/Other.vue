<template>
  
     
    <div class="wrapper">
        <div>
          <b><h3 id="other">Hobbies</h3></b>
            <p> Reading novels and books.<br> Cooking and baking.<br> Singing</p>   
        </div>
        <div>
           <b><h3>Attributes</h3></b> 
          <p> Honest<br>Hardworking<br> Intergrity<br> Eager to learn new things.<br></p>
        </div>
     
    </div>
</template>
<script>
export default {
    
}
</script>

<style scoped>
 .wrapper{
            display:grid;
            grid-template-columns:50% 50%;
            grid-gap: .15em;
           /* grid-auto-rows: 100px;*/
           grid-auto-rows: minmax(100px, auto);
        }
                                                                             
  .wrapper >div{
           background-color: #c4c4c4;
            padding: 1em;
        }
  .wrapper >div:nth-child(odd){
            background:#c4c4c4;
        }
       
</style>


