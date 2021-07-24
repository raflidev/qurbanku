<template>
  <div>
    <div class="w-full">
      <Navbar/>
      <section class="w-full md:w-3/4 mx-auto mt-14 md:mt-28 flex justify-between items-center">
        <div class="w-full md:w-2/5 items-center p-3 md:p-0">
          <h1 class="font-bold text-4xl md:text-5xl leading-snug">Siap Kurban <br> Tahun Depan!</h1>
          <p class="text-xl mt-5 mb-4">Program Nabung 10.000 Rupiah, Siapapun Berkenan Berkurban</p>
          <div>
            <button class="w-full md:w-auto px-4 py-2 bg-yellow-400 rounded-lg font-semibold">Mulai Nabung, Gratis!</button>
          </div>
        </div>
        <div class="w-1/2 hidden md:inline">
          <img src="image/cow.png" width="700" alt="sapi kurban">
        </div>
      </section>
      <section class="mt-20">
        <h1 class="font-semibold text-sm uppercase text-center">Telah dipercaya Oleh Beberapa Perusahaan Ternama</h1>
          <div class="flex justify-center py-6">
            <div class="grid grid-flow-col grid-cols-2 md:grid-cols-1 grid-rows-2 md:grid-rows-1 gap-6">
              <img src="/vendor/ovo.png" width="80" alt="ovo" data-aos="fadeup" data-aos-duration="5000">
              <img src="/vendor/kitabisacom.png" width="120" alt="kitabisa" data-aos="fadeup" data-aos-duration="800">
              <img src="/vendor/jenius.png" width="100" alt="jenius" data-aos="fadeup" data-aos-duration="1000">
              <img src="/vendor/gojek.png" width="100" alt="gojek" data-aos="fadeup" data-aos-duration="1200">
            </div>
          </div>
       
      </section>

      <section class="mt-20">
        <div class="w-3/4 mx-auto">
          <h1 class="text-center text-3xl font-bold">Daftar Paket</h1>
          <div class="flex flex-wrap justify-center items-center space-y-10 md:space-x-10 my-12">
            <div class="w-full md:w-1/4 bg-yellow-100 py-4 px-6 rounded mt-0 md:-mt-10" data-aos="fade-up" data-aos-duration="500">
              <div class="text-xs pb-3 text-center">Rekomendasi</div>
              <h2 class="text-center font-semibold h-full rounded pb-3">Qurban Standar</h2>
              <p class="text-center text-2xl font-bold">Rp 1.850.000</p>
              <ul class="mt-5">
                <li>Kambing / Domba</li>
                <li>Berat 18-20 kg</li>
              </ul>
              <div class="mt-4">
                <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
              </div>
            </div>
            <div class="w-full md:w-1/4 bg-gray-100 py-4 px-6 rounded" data-aos="fade-up" data-aos-duration="1000">
              <h2 class="text-center font-semibold h-full rounded pb-3">1/7 Sapi</h2>
              <p class="text-center text-2xl font-bold">Rp 2.350.000</p>
              <ul class="mt-5">
                <li>Sapi</li>
                <li>Berat 210-230 kg</li>
              </ul>
              <div class="mt-4">
                <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
              </div>
            </div>
            <div class="w-full md:w-1/4 bg-gray-100 py-4 px-6 rounded" data-aos="fade-up" data-aos-duration="1000">
              <h2 class="text-center font-semibold h-full rounded pb-3">Sapi</h2>
              <p class="text-center text-2xl font-bold">Rp 16.000.000</p>
              <ul class="mt-5">
                <li>Sapi</li>
                <li>Berat 200-230 kg</li>
              </ul>
              <div class="mt-4">
                <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-yellow-100 mt-20">
        <div class="w-3/4 mx-auto py-12">
          <div class="flex flex-wrap justify-center space-y-5 md:space-x-4">
              <img src="https://avatars.githubusercontent.com/u/17506770?v=4" width="150" class="rounded-xl" alt="david" data-aos="fade-right">
              <div class="w-full md:w-2/5 space-y-5" data-aos="fade-left">
                <p class="font-semibold text-xl">
                  Qurbanku Membantu Saya dan Rekan-Rekan Saya Untuk Patungan Sapi Untuk Qurban Dari Nabung 10.000 Perhari, Dan itu Luar Biasa. 
                </p>
                <p class="uppercase text-sm"><span class="font-medium">— David Tippett,</span> Karyawan OVO</p>
              </div>
          </div>
        </div>
      </section>

      <section class="w-3/4 mx-auto mt-24">
        <h1 class="text-center text-3xl font-bold">Qurbanku Juga Menyediakan Aqiqah</h1>
        <div class="flex flex-wrap justify-center items-center space-y-10 space-x-0 md:space-y-0 md:space-x-10 my-16">
          <div class="w-full md:w-1/4 bg-gray-100 py-4 px-6 rounded" data-aos="fade-up" data-aos-duration="1000">
            <h2 class="text-center font-semibold h-full rounded pb-3">Aqiqah Standar</h2>
            <p class="text-center text-2xl font-bold">Rp 2.300.000</p>
            <ul class="mt-5">
              <li>250 Tusuk Sate</li>
              <li>80 Gule</li>
            </ul>
            <div class="mt-4">
              <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
            </div>
          </div>
          <div class="w-full md:w-1/4 bg-yellow-100 py-4 px-6 rounded mt-0 md:-mt-5" data-aos="fade-up" data-aos-duration="500">
          <div class="text-xs pb-3 text-center">Rekomendasi</div>
            <h2 class="text-center font-semibold h-full rounded pb-3">Aqiqah Super</h2>
            <p class="text-center text-2xl font-bold">Rp 2.400.000</p>
            <ul class="mt-5">
              <li>300 Tusuk Sate</li>
              <li>100 Gule</li>
            </ul>
            <div class="mt-4">
              <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
            </div>
          </div>
          <div class="w-full md:w-1/4 bg-gray-100 py-4 px-6 rounded" data-aos="fade-up" data-aos-duration="1000">
            <h2 class="text-center font-semibold h-full rounded pb-3">Aqiqah Istimewa</h2>
            <p class="text-center text-2xl font-bold">Rp 3.150.000</p>
            <ul class="mt-5">
              <li>450 Tusuk Sate</li>
              <li>140 Gule</li>
            </ul>
            <div class="mt-4">
              <button class="px-4 py-2 rounded-md font-semibold text-center bg-yellow-400 w-full text-sm">Lihat Selengkapnya</button>
            </div>
          </div>
        </div>
      </section>
      <section class="mt-52 pb-5 w-3/4 mx-auto">
        <div class="flex flex-wrap justify-between">
          <div class="w-full md:w-1/4 mb-4 md:mb-0">
            <h1 class="text-2xl font-bold">Qurbanku</h1>
            <p class="mt-4">
              Qurbanku adalah platform untuk menabung qurban sekaligus marketplace untuk membeli langsung qurban dan aqiqah
            </p>
            <p class="mt-3">
              &copy; 2021 Qurbanku
            </p>
          </div>
          <div class="w-full md:w-3/4 flex flex-wrap justify-start md:justify-end space-y-5 md:space-y-0 space-x-0 md:space-x-10">
            <div>
              <h2 class="font-semibold text-xl">Produk</h2>
              <ul class="mt-3 space-y-2">
                <li class="hover:underline"><a href="#">Nabung Qurban</a></li>
                <li class="hover:underline"><a href="#">Qurban</a></li>
                <li class="hover:underline"><a href="#">Aqiqah</a></li>
              </ul>
            </div>
            <div>
              <h2 class="font-semibold text-xl">Perusahaan</h2>
              <ul class="mt-3 space-y-2">
                <li class="hover:underline"><a href="#">Syarat & Ketentuan</a></li>
                <li class="hover:underline"><a href="#">Kebijakan Privasi</a></li>
                <li class="hover:underline"><a href="#">FAQ</a></li>
              </ul>
            </div>
            <div>
              <h2 class="font-semibold text-xl">Sosial Media</h2>
              <ul class="mt-3 space-y-2">
                <li class="hover:underline"><a href="#">Facebook</a></li>
                <li class="hover:underline"><a href="#">Instagram</a></li>
                <li class="hover:underline"><a href="#">Youtube</a></li>
              </ul>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<style>
body{
  font-family: 'Poppins', sans-serif;
}

</style>

<script>
export default {}
</script>
