<template>
    <div class="limit-width center text-center pb-100 pink-links">
        <p class="pb-20" style="font-size: 18px;">If you are interested in working with me, hiring me, consulting on a project or maybe just need some technical insight...   please feel free to reach out.  I very much enjoy helping people find solutions to problems or, at least, connecting them with resources who can assist.</p>
        <p class="pb-20"><a href="mailto:info@philiptheobald.com">info@philiptheobald.com</a></p>
        <!-- <p class="pb-20" style="font-size: 36px;" className="contact-number">312-802-2423</p> -->
        <p class="pb-20" style="font-size: 16px;">
            You can also add or follow me on
            <a href="https://www.linkedin.com/in/philiptheobald/" target="blank">LinkedIn</a>,
            <!-- <a href="https://www.facebook.com/fylzero" target="blank">Facebook</a>, -->
            <a href="https://twitter.com/fylzero" target="blank">Twitter</a>,
            <a href="https://www.youtube.com/fylzero/videos" target="blank">YouTube</a>
            and
            <a href="https://www.instagram.com/fylzero/" target="blank">Instagram</a>.
        </p>
    </div>
</template>

<script>
export default {
    props: ['dark'],
    mounted() {
        //Scrolls to top when view is displayed
        document.getElementById('sandbox').scrollTop = 0;
    }
}
</script>
