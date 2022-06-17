<template>
  <section>
        <h2>Subscribe <span style="color:var(--primary-color)">&</span> Receive A Free eBook</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi eius beatae nam incidunt sint</span>
        <div class="content">
            <input type="text" placeholder="  insert your email ...*">
            <a href="#">Subscribe</a>
        </div>
        <small>Lorem ipsum, dolor sit amet consectetur adipisicing elit</small>
        
  </section>
</template>

<script>
export default {
    name:'SectionEbook'
}
</script>

<style lang="scss" scoped>
section{
    row-gap: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    margin-top: 150px;
    background-color: white;
    background-image: url("@/assets/img/subscribe-sec-bg.png");
    background-size: cover;
    height: 700px;

    h2{
        color: var(--tertiary-color);
        font-family: 'Playfair Display', serif;
    }

    input{
        width: 20%;
        height: 40px;
        border-radius: 3px;
        margin-right: 30px;
        border-color: #edede7;
    }
    a{
        text-decoration: none;
        text-transform: uppercase;
        padding: 12px 40px;
        background-color: var(--primary-color);
        color: white;
        font-weight: bold;
    }
    small,span{
        color: var(--secondary-color);
    }
}
</style>