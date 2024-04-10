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

    <section class="services p-4">
        <div class="container">
            <div class="container_top p-3">
                <h6 class="fw-bold">Our business areas</h6>
                <h2>Excellence in <span> Services</span></h2>
                <div class="text_services d-flex justify-content-between">
                    <p style="width:60%; margin-top: 30px; margin-bottom: 16px; color: rgb(182 182 182);">We are leaders
                        in providing consultancy services with a set of cutting-edge
                        technologies and a team
                        of
                        experienced and renowned professionals. These are some options that you can hire.</p>
                    <button class="btn_left">SEE ALL</button>
                </div>
            </div>
            <div class="row gap-3 m-2">
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">

                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M815 592h145q26 0 45 19t19 45v320q0 26-19 45t-45 19H640q-26 0-45-19t-19-45V656q0-26 19-45t45-19h113v-38H270v38h114q26 0 45 19t19 45v320q0 26-19 45t-45 19H64q-26 0-45-19T0 976V656q0-26 19-45t45-19h144v-60q0-15 16-24t37-9h220v-36H343q-26 0-45-19t-19-45V79q0-26 19-45t45-19h320q26 0 45 19t19 45v320q0 26-19 45t-45 19H545v37q41 0 108-.5t109-.5q21 0 37 8.5t16 24.5v60zm145 64H640v320h320V656zM663 79H343v320h320V79zM384 656H64v320h320V656z"
                                    fill=" rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v1040H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Audit & Assurance</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">
                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M960 159H704V97q0-26-12.5-48t-35-35T608 1H416q-40 0-68 28.5T320 97v62H64q-26 0-45 19T0 223v672q0 26 19 45t45 19h896q26 0 45-19t19-45V223q0-17-8.5-31.5T992 168t-32-9zM384 97q0-13 9.5-22.5T416 65h192q14 0 23 9.5t9 22.5v62H384V97zM64 223h896v225H608v-33q0-17-9-32t-23.5-23.5T544 351h-64q-27 0-45.5 19T416 415v33H64V223zm480 353h-64V415h64v161zM64 895V512h352v64q0 27 18.5 45.5T480 640h64q17 0 31.5-8.5T599 608t9-32v-64h352v383H64z"
                                    fill="rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v960H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Financial Advisory</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">

                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M256 320H32q-13 0-22.5 9.5T0 352v640q0 13 9.5 22.5T32 1024h224q13 0 22.5-9.5T288 992V352q0-13-9.5-22.5T256 320zm-32 640H64V384h160v576zm384-450H384q-14 0-23 9.5t-9 22.5v450q0 13 9 22.5t23 9.5h224q13 0 22.5-9.5T640 992V542q0-13-9.5-22.5T608 510zm-32 450H416V574h160v386zM960 0H736q-13 0-22.5 9.5T704 32v960q0 13 9.5 22.5t22.5 9.5h224q13 0 22.5-9.5T992 992V32q0-13-9.5-22.5T960 0zm-32 960H768V64h160v896z"
                                    fill=" rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v1040H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right "></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Analytics and M&A</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row gap-3 m-2 ">
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">

                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M934 66q13 0 22 3 2 6 2.5 15t-1 23-11 31-25.5 33L690 402l2 28q4 76 16 260 9 161 10 166 0 6-4 11-7 7-18 20t-24 27q-59-157-98-267l-35-94-71 71-130 125-19 19v25q-1 19 0 90v54l1 1 2 1q-6-10-8-14l-6-9q-58-92-68-109l-9-13-13-9q-68-41-135-84 1 0 2 2l1 1h67.5l9.5.5 10.5.5H231l26-1 18-18 126-130 71-71-94-34q-109-40-269-100 14-14 26.5-25t20.5-17l7-4h2q7 0 180 11 189 13 249 16l29 2 231-231q37-37 80-37zm0-64q-31 0-63.5 13.5T809 58L598 268q-32-2-88.5-5.5t-112.5-7-108-7-85.5-5.5-35.5-2h-5q-6 0-12.5 1t-16.5 5-19 12l-73 66q-19 19-16 41 2 22 26 32 63 25 304 113L230 641h-20q-21 0-66.5-.5T88 640H73.5l-5 .5L62 642l-8 3.5-10 5.5-11.5 7.5L19 669l-3 3Q2 687 1 704t14 29q22 18 170 107 11 18 73 116 28 46 30 49 10 16 29 17h1q18 0 35-17 7-8 12.5-15.5T374 976l5-10 2.5-8.5 1-6.5v-5l-.5-3q1-10 .5-69t.5-79l130-126q23 63 65 177t47 125q9 23 31 26h5q9 0 18.5-4.5T697 980q5-5 13.5-14t26-28.5T763 907q20-24 18-54 0-2-4.5-82t-11-187.5T756 427l211-211q26-27 40.5-57.5T1023 102t-4.5-47-16.5-31Q980 2 934 2z"
                                    fill=" rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v1040H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Middle Marketing</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">

                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M850 414q0-36-5.5-71t-16-68.5T803 210t-35-60-44-55-52.5-48.5T612 5q-8-5-16.5-5t-16 4.5T568 16q-7 12-3.5 24.5T579 60q97 57 152 151t55 203q0 90-31.5 168t-87 133-133 86.5T367 833q-13 0-26.5-1t-27-2.5-26.5-4-25.5-6T236 812t-25-9-24.5 0-17.5 17 .5 24.5T187 862q86 35 180 35h1v63h-93q-14 0-24 9t-10 22.5 10 23 24 9.5h253q14 0 23.5-9.5t9.5-23-9.5-22.5-23.5-9h-97v-67q186-22 302.5-154T850 414zm-131 3q0-57-17.5-111t-50-97.5-76-76T478 82 367 64q-72 0-137 28t-112.5 75.5-75 113T15 417q0 96 47 177t128 128 177 47q72 0 137-28t112.5-75 75-112T719 417zm-641 0q0-78 39-144.5T222.5 167 367 128q119 0 203.5 85T655 417q0 59-22.5 112T571 620.5 479 682t-112 23q-119 0-204-84.5T78 417z"
                                    fill=" rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v1040H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Legal Consulting</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
                <div class="col card border border-0">
                    <div class="card-body">
                        <div class="d-flex justify-content-between svg_container">

                            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 1024 1040">
                                <path
                                    d="M1023 446L905 39q-1-7-6-12.5T888 18t-13-3H139q-7 0-13.5 3t-11 8.5T108 39L1 426q-1 5-.5 10.5T3 447q-3 10-3 18v352q0 26 18.5 45T64 881h896q27 0 45.5-19t18.5-45V460q0-8-1-14zM164 79h686l93 322H645q0 23-6.5 43T620 480t-28 27.5-36.5 17.5-43.5 6q-29 0-53-9.5T417.5 495 390 454t-10-53H74zm796 738H64V465h263q21 61 70 95.5T512 595q44 0 81.5-15.5t64-45T698 465h262v352z"
                                    fill=" rgb(5, 130, 131)" />
                                <path fill="rgba(0, 0, 0, 0)" d="M0 0h1024v1040H0z" />
                            </svg>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <div class="text_card">
                            <h5 class="card-title fw-semibold m-3">Regulatory Risk</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>

</template>


<style>
.jumbotron {
    background-image: url(/img/bg-parallax.png);
    background-position: center top;
    text-align: center;
    background-size: cover;
    height: 800px;
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

.center-jumbotron {




    p {
        width: 380px;
        margin-top: 30px;
        margin-bottom: 40px;
        color: rgb(182 182 182);

    }


}

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
</style>