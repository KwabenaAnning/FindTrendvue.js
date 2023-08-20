<script setup>
  import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
    <div class="card1">
        <div class="flashtrend">
            <div class="flash">
            <img src="@/components/images/Vector.svg" alt="">
            </div>
            <div class="findtrend">
            <p>findtrend</p>
            </div>
        </div>
        <div class="list">
            <ul>
                 <li><a href="link">About</a></li>
                <li><a href="link">How it works</a></li>
                <li><a href="link">Pricing</a></li>
                <li><a href="link">Solution</a></li>
                <li><a href="link">Features</a></li>
            </ul>
        </div>
        <div class="logReg">
             <p>login</p>
            <ButtonComponent class="register" buttonText= "register"/>
        </div>
        <div class="hambaga">
            <img src="@/components/images/humburgersign.png" alt="">
        </div>
    </div> 
</template>

<style scoped>

.card1{
    display: flex;
    justify-content: center;
    justify-content: space-between;
    display:flex;
    color: #FFF;
    padding: 20px;
    align-items: center;
}

.flashtrend{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
}

.list ul {
    display: flex;
    list-style-type: none;
    text-decoration: none;
    justify-content: space-between;
    justify-content: space-evenly;
    gap: 40px;
    text-align: center;
}
   
.list ul a{
    display: flex;
    justify-content: center;
    text-decoration: none;
}

.logReg{
  display: flex;
  align-items: center;
  gap: 40px;
}

.register{
    border: none;
}

.hambaga{
 display: none;
}

/* .navremove{
    display: flex;
    justify-content: space-between;
    align-items: center;
} */


@media (max-width:900px) {
    .list ul {
    display: flex;
    list-style-type: none;
    text-decoration: none;
    gap: 20px;
    text-align: center;
} 

.logReg{
  display: flex;
  align-items: center;
  gap: 20px;
}

}
@media (max-width:680px) {
    .list ul {
    display: flex;
    font-size: 14px;
    list-style-type: none;
    text-decoration: none;
    gap: 5px;
    text-align: center;}

    .logReg{
  display: flex;
  align-items: center;
  gap: 5px;
}
}
@media (max-width: 610px) {
    .hamabaga{
        display: flex;
        flex-direction: row;
        align-items: right;
       
    }

    .navremove{
    display:none ;
  }
  .findtrend{
    display: none;
  }
  
  .logReg{
    display: none;
  }

  .list{
    display: none;
  }

  .hambaga{
    display: flex;
    flex-direction: row;
  }
}
/* .nav{
  display:flex;
  color: #FFF;
  padding: 30px;
 
}

.AHPSF{
    display: flex; 
    justify-content: space-between;
    gap: 40px;
    list-style-type: none;
}

.logReg{
    display: flex; 
    justify-content: space-evenly;
    gap: 40px;
}

.humburger{
    display: none;
}

@media (max-width:600px) {
   .navRemove{
    display: none;
}  
    
   .humburger{
    display: flex;
    color: white;
    align-items: right;
}
} */
</style> 

