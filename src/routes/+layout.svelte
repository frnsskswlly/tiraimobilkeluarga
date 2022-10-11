<script>
    import "../app.css"
    let src = '/siang.jpg';
</script>

<div class="grid place-items-center text-[#111827] fixed top-0 left-0 right-0 md:w-[100%] z-50">
    <nav class="w-[100%] mx-auto bg-[#ffd859] text-center p-2 md:space-x-6 font-bold">
        <a href="/">🛖 Beranda</a>
        <a href="/gallery">🗃️ Gallery</a>
        <a class="align-top" href="https://wa.me/6281522612891?text=Hallo%20Tirai%20Mobil%20Keluarga%20!">📞 Hubungi Kami</a>
    </nav>
</div>

<div class="mt-24 md:w-[640px] grid place-items-center mx-auto text-center text-[#d9e6eb] md:mt-18">   
    <img class="w-40 md:w-60 rounded-full mb-6" src={src} alt="">
    <h1 class="text-2xl md:text-3xl font-bold mb-3 text-[#ffd859]">Tirai Mobil Keluarga</h1>
    <p class="">Kami menyediakan tirai mobil berkualitas premium. Sudah berdiri sejak 2006, dan memiliki lebih dari 100.000 pelanggan.</p>
</div>

<div class="md:w-[640px] md:justify-center mx-auto text-center flex flex-col space-y-3 mt-6 mb-3 md:flex-row md:mt-9 md:mb-6 md:space-x-3 md:space-y-0 font-bold">
    <a class="border-2 border-[#5fd470] bg-[#5fd470] text-[#111827] px-6 py-4 rounded-md" href="https://www.tokopedia.com/tiraimobilkeluarga" target="_blank">Tokopedia</a>
    <a class="border-2 border-[#164ecb] bg-[#164ecb] text-[#d9e6eb] px-6 py-4 rounded-md" href="https://www.lazada.co.id/shop/tirai-mobil-keluarga" target="_blank">Lazada</a>
    <a class="border-2 border-[#ee4d2d] bg-[#ee4d2d] text-[#d9e6eb] px-6 py-4 rounded-md" href="https://www.shopee.co.id/tiraimobilkeluarga" target="_blank">Shopee</a>
</div>


<slot></slot>

<footer class="text-center text-[#d9e6eb] py-9 mx-auto">
    <div class="mb-5 flex mx-auto justify-center space-x-3">
        <a href="https://www.instagram.com/tiraimobilkeluarga"><svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
            width="30" height="30"
            viewBox="0 0 50 50"
            style=" fill:#ffd859;">    <path d="M 16 3 C 8.83 3 3 8.83 3 16 L 3 34 C 3 41.17 8.83 47 16 47 L 34 47 C 41.17 47 47 41.17 47 34 L 47 16 C 47 8.83 41.17 3 34 3 L 16 3 z M 37 11 C 38.1 11 39 11.9 39 13 C 39 14.1 38.1 15 37 15 C 35.9 15 35 14.1 35 13 C 35 11.9 35.9 11 37 11 z M 25 14 C 31.07 14 36 18.93 36 25 C 36 31.07 31.07 36 25 36 C 18.93 36 14 31.07 14 25 C 14 18.93 18.93 14 25 14 z M 25 16 C 20.04 16 16 20.04 16 25 C 16 29.96 20.04 34 25 34 C 29.96 34 34 29.96 34 25 C 34 20.04 29.96 16 25 16 z"></path></svg></a>
        <a href="https://www.facebook.com/tiraimobilkeluarga"><svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
            width="30" height="30"
            viewBox="0 0 50 50"
            style=" fill:#ffd859;">    <path d="M41,4H9C6.24,4,4,6.24,4,9v32c0,2.76,2.24,5,5,5h32c2.76,0,5-2.24,5-5V9C46,6.24,43.76,4,41,4z M37,19h-2c-2.14,0-3,0.5-3,2 v3h5l-1,5h-4v15h-5V29h-4v-5h4v-3c0-4,2-7,6-7c2.9,0,4,1,4,1V19z"></path></svg></a>
        <a href="https://www.tiktok.com/@tiraimobilkeluarga"><svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
            width="30" height="30"
            viewBox="0 0 50 50"
            style=" fill:#ffd859;">    <path d="M41,4H9C6.243,4,4,6.243,4,9v32c0,2.757,2.243,5,5,5h32c2.757,0,5-2.243,5-5V9C46,6.243,43.757,4,41,4z M37.006,22.323 c-0.227,0.021-0.457,0.035-0.69,0.035c-2.623,0-4.928-1.349-6.269-3.388c0,5.349,0,11.435,0,11.537c0,4.709-3.818,8.527-8.527,8.527 s-8.527-3.818-8.527-8.527s3.818-8.527,8.527-8.527c0.178,0,0.352,0.016,0.527,0.027v4.202c-0.175-0.021-0.347-0.053-0.527-0.053 c-2.404,0-4.352,1.948-4.352,4.352s1.948,4.352,4.352,4.352s4.527-1.894,4.527-4.298c0-0.095,0.042-19.594,0.042-19.594h4.016 c0.378,3.591,3.277,6.425,6.901,6.685V22.323z"></path></svg></a>
    </div>
    <p>Copyright &copy; 2022 Tirai Mobil Keluarga by <span class="font-bold">Artha Agung.</span></p>
</footer>
