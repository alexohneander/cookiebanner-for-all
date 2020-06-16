<template>
    <div class="cookiebanner-box open">
        <div class="cookiebanner-box__inner">
            <img src="https://www.pulse-advertising.com/wp-content/themes/pulse/assets/images/cookies_image.png">
            <div class="title uppercase">Have a Cookie</div>

            <div class="desc">We use cookies. Just to track the performance of the website, and to provide a better user experience. We store no personal details. <br><br> Read our <a href="https://www.pulse-advertising.com/privacy/">Cookie Statement</a> for more details. <a class="accept_cookies">Accept cookies.</a>        </div>

            <div class="button">
                <button class="accept_cookies">Accept Cookies</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Banner'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .cookiebanner-box{
        position: fixed;
        bottom: 100px;
        background: black;
        width: 255px;
        z-index: 20000;
        color: white;
    }

    .cookiebanner-box.open{
        transition: all 0.6s ease-out 0.3s;
        right: 50px;
    }

    .cookiebanner-box .cookiebanner-box__inner{
        position: relative;
        padding: 40px 40px 30px 40px;
        text-align: center;
    }
</style>