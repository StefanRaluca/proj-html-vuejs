<script>
export default {
    name: 'HeaderApp',
    data() {
        return {
            openingHours: '09:00 - 18:00',
            openingDay: 'Mon-Sat-',
            phoneNumber: '+1(305) 1234-5678',
            emailAddress: 'hello@example.com'
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
</style>
