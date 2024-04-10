<script>
export default {
    name: 'latestSectionMain',

}
</script>
<template>
    <section>
        <div class="container-fluid text-center top_container_results text-white">
            <h6>WHAT ARE WE DOING</h6>
            <h2> <span>Results </span> in Numbers</h2>
            <div class="results_number d-flex">
                <div class="number_results_element">
                    <p>128</p>
                    <h4>Certifications</h4>
                </div>
                <div class="number_results_element">
                    <p>230</p>
                    <h4>Employees</h4>
                </div>
                <div class="number_results_element">
                    <p>517</p>
                    <h4>Customers</h4>

                </div>
                <div class="number_results_element">
                    <p>94</p>
                    <h4>Countries Served</h4>

                </div>
            </div>

        </div>
        <div class="container_results_logo">
            <div class="img_container_logo d-flex">
                <img src="/img/logo-4.png" alt="Immagine 1">
                <img src="/img/logo-5.png" alt="Immagine 2">
                <img src="/img/logo-1.png" alt="Immagine 3">
                <img src="/img/logo-2.png" alt="Immagine 4">
                <img src="/img/logo-3.png" alt="Immagine 5">
                <img src="/img/logo-4.png" alt="Immagine 6">
            </div>
        </div>
    </section>
</template>
<style>
.top_container_results {
    background-image: url(/img/bg-7.jpg);
    background-size: cover;
    background-position: center;
    padding: 50px 0;

    h6 {
        font-size: 12px;
        color: var(--bool--buttons--principal);
        margin-bottom: 20px;
    }

    h2 {
        font-weight: 900;
        font-size: 40px;
    }

    span {
        background-color: #0E272D;
        color: white;
        margin-right: 5px;
    }

    p {
        font-weight: 800;
        font-size: 30px;
        color: var(--bool--buttons--principal);
    }

    h4 {
        font-weight: 700;
        font-size: 25px;
    }
}

.results_number {
    width: 70%;
    margin: auto;
    height: 250px;
    justify-content: center;
    align-items: center;



    .number_results_element {
        width: 23%;
        margin-bottom: 20px;
    }
}





.container_results_logo {
    background-color: #111117;
    background-size: auto 100%;
    background-repeat: no-repeat;
    background-position: center;
    padding: 20px;



    .img_container_logo {
        justify-content: space-evenly;
        margin-top: 41px;
        width: 70%;
        margin: auto;
        height: 200px;

        img {
            filter: invert(49%) sepia(5%) saturate(163%) hue-rotate(202deg) brightness(93%) contrast(85%);
            width: 10%;
            object-fit: contain;
        }



    }
}
</style>