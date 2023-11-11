<template>
    <div class="footer-bg text-white">
        <div class="d-flex justify-content-between position-relative overflow-hidden">
            <div class="container d-flex py-5">
                <div>
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h2>Shop</h2>
                        </li>
                        <li>
                            <a href="#">Shop DC</a>
                        </li>
                        <li>
                            <a href="#">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </div>
                <div class="d-flex">
                    <ul>
                        <li>
                            <h2>DC</h2>
                        </li>
                        <li>
                           <a href="#">Terms Of Use Privacy policy (New)</a> 
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h2>sites</h2>
                        </li>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="img position-absolute">
                <img src="/Images/dc-logo-bg.png" alt="">
            </div>
        </div>

    </div>
</template>
  
<script>
export default {
    data() {
        return {

        }
    }
}
</script>
  
<style lang="scss" scoped>
.footer-bg {
    background-image: url("/Images/footer-bg.jpg");
    background-size: cover;
}

h2 {
    text-transform: uppercase;
}

li {
    list-style: none;
    padding: 2px 0px;

    a {
        text-decoration: none;
        color: rgb(255, 255, 255, 0.5);
    }
}

.img {
    width: 600px;
    right: 100px;
    top: -80px
}

img {
    width: 100%;
}
</style>