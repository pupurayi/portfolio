<template>
    <h3 id="inspiration">Inspiration</h3>
  <p>
   My inspiration comes from those who have made it and im confident that one day I will testify. These are the quotes that keep me going, whenever i feel i cant make it
   i always get back to them.
   <ul>
   <li>There is nothing impossible to him who try.<i>Alexander the Great</i></li>
   <li>The journey of a thousand miles begins with one step.<i>Lao Tzu</i></li>
   <li>If my mind can conceive it,and my heart can believe it - then i can achieve it.<i>Muhammed Ali</i></li>
   <li> His grace is always sufficient!</li>
   </ul>
 </p> 
</template>

<script>
export default {
    data:()=>({
         
    })
}
</script>

<style scoped>
ul {
  list-style: none; /* Remove default bullets */
}

ul li::before {
  content: "\2022";  /* Add content: \2022 is the CSS Code/unicode for a bullet */
  color: #751c92; /* Change the color */
  font-weight: bold; /* If you want it to be bold */
  width: 1em; /* Also needed for space (tweak if needed) */
  margin-left: -1em; /* Also needed for space (tweak if needed) */
}

    p{
        text-align: left;
    }
</style>