<script>
export default {
    name: 'mainApp',

}
</script>

<template>
    <div class="jumbotron">
        <div class="center-jumbotron">
            <h1>Ready <span>Team</span></h1>
            <p>No matter what your company needs, we will be ready to assist you in the best possible way.
            </p>
            <button class="text-uppercase btn_left">Get in touch</button>
            <button class="text-uppercase btn_right">Read more</button>
        </div>
    </div>
</template>


<style>
.jumbotron {
    background-image: url(/img/bg-parallax.png);
    background-position: center top;
    text-align: center;
    background-size: cover;
    height: 1000px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-top: -160px;




    h1 {
        font-weight: 900;
        font-size: 50px;

        span {
            background-color: var(--bool--text--decoration);
            color: var(--bool--buttons--principal);

        }
    }
}

.center-jumbotron {
    .btn_left {
        text-align: center;
        height: 40px;
        width: 150px;
        border: none;
        color: white;
        background-color: var(--bool--buttons--principal);
        border-radius: 5px;
        margin-right: 15px;
    }

    .btn_right {
        text-align: center;
        height: 40px;
        width: 150px;
        border: none;
        color: var(--bool--buttons--principal);
        background-color: white;
        border: 1px solid var(--bool--buttons--principal);
        border-radius: 5px;

    }

    p {
        width: 380px;
        margin-top: 30px;
        margin-bottom: 40px;
        color: rgb(182 182 182);

    }

}
</style>