<script>
export default {
    name: 'HeaderApp',
    data() {
        return {
            openingHours: '09:00 - 18:00',
            openingDay: 'Mon-Sat-',
            phoneNumber: '+1(305) 1234-5678',
            emailAddress: 'hello@example.com',
            menuLinks: [
                { text: 'Home', link: '/home' },
                { text: 'Services', link: '/services' },
                { text: 'About', link: '/about' },
                { text: 'Projects', link: '/portfolio' },
                { text: 'Results', link: '/contact' }
            ],
            buttonText: 'Get in Touch',
            logoSrc: '/public/img/logo.png',
        };
    }
};

</script>


<template>
    <header>
        <div class="left">
            <div>
                <i class="fa-solid fa-clock"></i>
                <span>Open Hours: {{ openingDay }} {{ openingHours }}</span>
            </div>
        </div>

        <div class="right">
            <div>
                <i class="fa-solid fa-phone"></i>
                <span>{{ phoneNumber }}</span>
            </div>
            <div>
                <i class="fa-solid fa-envelope"></i>
                <span>{{ emailAddress }}</span>
            </div>
            <div class="social-media">
                <a href="#"><i class="fa-brands fa-facebook"></i></a>
                <a href="#"> <i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
            </div>
        </div>
    </header>
    <div class="lower-container">
        <div>
            <img :src="logoSrc" alt="Logo" class="logo">
        </div>
        <div class="nav-bar">
            <nav>
                <ul>
                    <li v-for="(link, index) in menuLinks" :key="index">
                        <a :href="link.link">{{ link.text }}</a>
                    </li>
                </ul>
                <button>{{ buttonText }}</button>
            </nav>

        </div>




    </div>

</template>

<style>
header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: var(--bool--header);
    color: var(--bool--primary);
    font-size: 14px;
    height: 30px;
}


.left {
    display: flex;
    align-items: center;

    .fa-clock {
        margin-right: 5px;
    }

}

.right {
    display: flex;
    gap: 25px;

    .fa-phone,
    .fa-envelope {
        margin-right: 5px;
    }
}

.right>div {
    margin-left: 20px;

}

.social-media {
    display: flex;
    gap: 25px;
    align-items: center;


    a {
        color: var(--bool--primary);
    }


}

.lower-container {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    padding: 10px;
    margin: 10px;


}

.logo {
    width: 40%;
    margin-left: 30px;
}

nav {
    display: flex;
    gap: 20px;



    ul {
        display: flex;
        gap: 35px;
        list-style: none;
        margin: 0;
        padding: 0;

        a {
            text-decoration: none;
            color: rgb(60, 60, 61);
            font-size: 20px;
        }
    }

    button {
        text-align: center;
        height: 40px;
        width: 150px;
        border: none;
        color: white;
        background-color: var(--bool--buttons--principal);
    }

    ul li {
        margin-right: 20px;
    }

    .nav-bar {
        width: 40%;
    }
}
</style>
