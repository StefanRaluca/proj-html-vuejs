<script>
export default {
    name: 'FooterApp',
    data() {
        return {
            footerDetails: {
                logo: {
                    src: '/svg/svg-7.svg',
                    alt: 'Logo',
                    details: 'A Functional HTML Template for Corporate & Business'
                },
                numberPhone: '+1(305) 1234-5678',
                emailAddress: 'hello@example.com',
                address: 'Main Avenue, 987',
                buttonText: 'Get in Touch',
                about: [
                    { text: 'The Company', link: '#' },
                    { text: 'Institutional', link: '#' },
                    { text: 'Social & Events', link: '#' },
                    { text: 'Innovation', link: '#' },
                    { text: 'Environment', link: '#' },
                    { text: 'Technology', link: '#' },
                ],
                services: [
                    { text: 'Audit & Assurance', link: '#' },
                    { text: 'Financial Advisory', link: '#' },
                    { text: 'Analytics M&A', link: '#' },
                    { text: 'Middle Marketing', link: '#' },
                    { text: 'Legal Consulting', link: '#' },
                    { text: 'Regulatory Risk', link: '#' },
                ],
                support: [
                    { text: 'Responsibility', link: '#' },
                    { text: 'Terms of Use ', link: '#' },
                    { text: 'About Cookies', link: '#' },
                    { text: 'Privacy Policy', link: '#' },
                    { text: 'Accessibility', link: '#' },
                    { text: 'Information', link: '#' },
                ]
            }
        };
    }
};
</script>
<template>
    <footer class="footer">
        <div class="container">
            <div class="row" style="padding: 50px;">
                <div class="col">
                    <div class="logo_section">
                        <img :src="footerDetails.logo.src" :alt="footerDetails.logo.alt" class="footer-logo">
                        <p>{{ footerDetails.logo.details }}</p>

                        <p><i class="fa-solid fa-phone me-2"></i>{{ footerDetails.numberPhone }}</p>
                        <p><i class="fa-solid fa-envelope me-2"></i>{{ footerDetails.emailAddress }}</p>
                        <p><i class="fa-solid fa-location-dot me-2"></i>{{ footerDetails.address }}</p>
                        <button class="btn_footer">{{ footerDetails.buttonText }}</button>

                    </div>
                </div>
                <div class="col about_section">
                    <h4>About</h4>
                    <ul class="list-unstyled">
                        <li v-for="(link, index) in footerDetails.about" :key="'about' + index">
                            <a :href="link.link">> {{ link.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col services_section">
                    <h4>Services</h4>
                    <ul class="list-unstyled">
                        <li v-for="(link, index) in footerDetails.services" :key="'services' + index">
                            <a :href="link.link">> {{ link.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col support_section">
                    <h4>Support</h4>
                    <ul class="list-unstyled">
                        <li v-for="(link, index) in footerDetails.support" :key="'support' + index">
                            <a :href="link.link" class="no-underline"> > {{ link.text }}</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
    <div class="footer_bottom">
        <div class="container">
            <div class="row">
                <div class="col d-flex justify-content-around align-items-center">
                    <p>Enjoy the low price. We are tracking any intention of piracy.</p>
                    <p>© 2020 NEXGEN is Proudly Powered by <span style="color: var(--bool--buttons--principal);">Codings
                        </span> .</p>
                    <div class="text-end">
                        <i class="fa-solid fa-arrow-up"></i>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>
<style>
footer {
    background-color: #111117;
    color: rgb(182 182 182);

    .container {
        padding: 20px;
    }

    .btn_footer {
        text-align: center;
        height: 40px;
        width: 150px;
        border: none;
        color: white;
        background-color: black;
        border: 1px solid var(--bool--buttons--principal);
        border-radius: 5px;
    }
}

.logo_section {
    width: 80%;

    img {
        width: 60%;
    }

    p {
        margin-top: 10px;
        margin-bottom: 15px;
    }
}

.about_section,
.services_section,
.support_section {
    color: white;
    background-color: #19191F;
    border-radius: 15px;
    margin-right: 20px;

    h4 {
        margin-left: 25px;
        margin-top: 20px;
        font-weight: 700;
        font-size: 18px;
    }

    ul {
        padding: 0;
        margin: 0;
        list-style: none;

        li {
            padding: 5px 10px;
            color: rgb(182 182 182);
        }

        a {
            text-decoration: none;
            color: rgb(182 182 182);

        }
    }
}

.footer_bottom {
    background-color: #0D0D11;
    color: rgb(182 182 182);
    padding: 15px 0;

    p {
        text-align: center;
        font-size: 15px;
        margin-top: 10px;
    }
}





.fa-arrow-up {
    font-size: 30px;
    margin-left: 10px;
    background-color: #111117;
    border-radius: 50%;
    color: black;
    width: 40px;
    text-align: center;
    height: 30px;
}
</style>