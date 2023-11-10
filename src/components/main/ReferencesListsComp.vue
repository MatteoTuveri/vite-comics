<template>
    <div class="footer-bg py-5 text-white">
        <div class="container d-flex justify-content-between position-relative overflow-hidden">
            <div class="d-flex">
                <div>
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li>Characters</li>
                    </ul>
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li>Characters</li>
                    </ul>
                </div>
                <div class="d-flex">
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li>Characters</li>
                    </ul>
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li>Characters</li>
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

li {
    list-style: none;
}

.img{
    width: 20vw;
}

img{
    width: 100%;
}
</style>