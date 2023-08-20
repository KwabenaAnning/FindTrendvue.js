<template>
    <div class="footer">
        <div class="imgTrend">
            <img src="@/components/images/Vector.png" alt="">
            <p>Fintrend</p>
        </div>
        <div class="ptcc">
            <p> Privacy Policy</p>
            <p>Terms and Conditions</p>
            <p>Contact Us</p>
            <p>Careers</p>
        </div>
    </div>
</template>

<style scoped>

.imgTrend{
    display: flex;
    gap: 10px;
    align-items: center;
    color: #000;
    text-align: center;
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
    line-height: 100%; /* 24px */
}
.footer{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 41px 100px 41px 80px;
  
}

.ptcc{
    display: flex;
    gap: 40px;
}

@media (max-width:776px) {
      .footer{
    display: flex;
    gap: 100px;
    }
}

@media (max-width:610px) {
    .footer{
        display: flex;
        flex-direction: column;
        margin: 0 auto;
        gap: 107px;
    }

    .ptcc{
        display: flex;
        flex-direction: column;
        justify-content: center;
        margin: 0 auto;
        text-align: center;
    }
    .imgTrend{
        margin: 0 auto;
    }
}
</style>