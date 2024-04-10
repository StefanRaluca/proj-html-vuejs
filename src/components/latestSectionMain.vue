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

    <div class="container">
        <div class="row">
            <div class="col">
                <div class="container_contact_us">

                    <h6 class="mb-3 mt-2">SEND A MESSAGE</h6>
                    <h2 class="text-uppercase">Get in <span>Touch</span> </h2>
                    <p>We will respond to your message as soon as possible.</p>
                    <form>
                        <div class="form-group d-flex m-3 gap-2 ">
                            <input type="text" class="form-control border-0 bg-light rounded-0" placeholder="Name">
                            <input type="email" class="form-control border-0 bg-light rounded-0" placeholder="Email">
                        </div>
                        <div class="form-group d-flex m-3 gap-2">
                            <input type="text" class="form-control border-0 bg-light rounded-0" placeholder="Phone">
                            <select class="form-select border-0 bg-light rounded-0"
                                style="padding: 0.375rem 0.75rem !important;" aria-label="Default select example">
                                <option value="" disabled selected>More info</option>
                                <option value="1">One</option>
                                <option value="2">Two</option>
                                <option value="3">Three</option>
                            </select>
                        </div>
                        <div class="form-group m-3 gap-2">
                            <textarea class="form-control border-0 bg-light rounded-0" id="exampleInputMessage1"
                                rows="3" placeholder="Message"></textarea>
                        </div>
                        <button type="submit" class="btn_left" style="width: 80px !important;">SEND</button>
                    </form>
                </div>

            </div>

            <div class="col">
                <div class="contact-details">
                    <h5>Example Inc.</h5>
                    <p style="color: rgb(182 182 182);">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    <p style="color: rgb(182 182 182);">Praesent diam lacus, dapibus sed imperdiet consectetur.</p>
                    <p style="color: var(--bool--buttons--principal);"> <span class="rounded_design"><i
                                class="fa-solid fa-phone"></i></span>+1(305) 1234-5678</p>
                    <p style="color: var(--bool--buttons--principal);"> <span class="rounded_design"><i
                                class="fa-solid fa-envelope"></i></span>
                        hello@example.com</p>
                    <p style="color: var(--bool--buttons--principal);"> <span class="rounded_design"><i
                                class="fa-solid fa-location-dot"></i></span> Main Avenue, 987
                    </p>
                    <button class="btn_right">VIEW MAP</button>
                </div>
            </div>
        </div>
    </div>

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

col {
    h6 {
        font-weight: 700;
        margin-top: 1rem;

    }

    p {
        color: rgb(182 182 182);
        margin-bottom: 3rem;
        margin-top: 1rem;
        margin-left: 18px;
    }


}

.contact-details {
    width: 90%;
    margin: auto;
    padding: 50px;
    margin-top: 15px;
    line-height: 25px;

    h5 {
        font-size: 30px;
        font-weight: 600;
    }
}

.container_contact_us {
    width: 90%;
    margin: auto;
    padding: 50px;

}

.rounded_design {
    border-radius: 100%;
    background-color: var(--bool--text--decoration);
    color: var(--bool--buttons--principal);
    padding: 6px;
    margin-right: 0.5rem;
}
</style>