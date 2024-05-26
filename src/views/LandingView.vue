<template>
<div class="w-full py-2 bg-primary text-center text-black text-xs bg-yellow-400 sm:text-sm md:text-base lg:text-lg xl:text-l"> Dapatkan diskon 50% Sekarang </div>

<nav class="flex flex-wrap items-center justify-between px-2 py-3 sticky top-0 z-40 bg-white">
    <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
      <div class="w-full relative flex justify-between lg:w-auto  px-4 lg:static lg:block lg:justify-start">
        <a class="flex items-center text-base font-bold leading-relaxed mr-4 py-2 whitespace-nowrap uppercase text-yellow-400" href="#pablo">
            <img src="../assets/logo2.png" alt="Logo" class="w-10 mr-2 text-5xl">MINUSONE </a>
        <button class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none" type="button">
          <span class="block relative w-6 h-px rounded-sm bg-white"></span>
          <span class="block relative w-6 h-px rounded-sm bg-white mt-1"></span>
          <span class="block relative w-6 h-px rounded-sm bg-white mt-1"></span>
        </button>
      </div>
      <div class="lg:flex flex-grow items-center" id="example-navbar-warning">
        <ul class="flex flex-col lg:flex-row list-none ml-auto">
            <li class="nav-item">
              <a class=" cursor-pointer px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
                Beranda
              </a>
            </li>
            <li class="nav-item">
              <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
              Tentang
              </a>
            </li>
            <li class="nav-item">
              <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
               Produk
              </a>
            </li>
            <li class="nav-item">
              <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
                Pembayaran
              </a>
            </li>
        </ul>
        <!--icon botsrap-->
        <ul class="flex flex-col lg:flex-row list-none ml-auto">
          <li class="nav-item -mx-1">
                <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
                  <i class="bi bi-search-heart-fill text-2xl"></i>
                </a>
            </li>
            <li class="nav-item -mx-1">
                <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-yellow-400 hover:opacity-75" href="#pablo">
                  <i class="bi bi-bag-plus-fill text-2xl"></i>
                </a>
            </li> 
        </ul>
      </div>
    </div>
  </nav>


<!--background-->
<section id="section-1" class="relative">
    <img src="../assets/background-main.jpg" alt="" class="w-full lg:h-auto h-[265px] object-fill">
    <div class="absolute z-10 w-full top-1/4 lg:px-20 px-4">
        <div class="capitalize text-white text-xl lg:text-4xl tracking-wide leading-snug text-left hover:opacity-70 mt-18">
            <span class="font-bold">Gaya</span> Asli Buatan
            <br>
            <span class="font-bold">Negeri</span> Sendiri
            <br>
            <a href="#beli" class="bg-transparent hover:bg-yellow-400 text-yellow-300 font-bold hover:text-white py-2 px-4 border border-yellow-400 hover:border-transparent rounded-full text-xs lg:text-sm mt-4 inline-block">
                Beli Sekarang
            </a>
        </div>
    </div>
</section>


<!-- tentang -->
<section class="bg-netral p-6 rounded-lg container mx-auto px-4 py-8">
  <h2 class="text-2xl mb-4">Tentang</h2>
    <p class="mb-4">
      Pilihan tepat bagi Anda yang mencari sepatu berkualitas tinggi dengan sentuhan lokal yang unik. 
      Dibuat dengan cinta dan keterampilan oleh pengrajin-pengrajin terbaik di Indonesia, setiap pasang sepatu Minusone menggabungkan desain modern dengan kekayaan budaya lokal. 
      Kami menggunakan bahan-bahan terbaik yang tidak hanya nyaman di kaki, tetapi juga tahan lama untuk penggunaan sehari-hari. 
      Dari gaya kasual hingga formal, sepatu Minusone dirancang untuk menemani setiap langkah Anda dengan penuh percaya diri.
    </p>
    <p class="mb-4">
      Kami di Minusone sangat bangga dengan produk kami yang 100% buatan lokal. 
      Kami percaya bahwa sepatu yang baik bukan hanya tentang penampilan, tetapi juga tentang cerita di baliknya.
      Dengan memilih sepatu Minusone, Anda turut mendukung industri kreatif dalam negeri dan membantu para pengrajin lokal untuk terus berkarya.
    </p>
</section>



<!-- keuntungan -->
<section class="py-8 lg:py-16 px-4 lg:px-20 bg-white">
  <h2 class="text-2xl lg:text-2xl font-semibold text-center mb-10">Keuntungan yang Kami Berikan</h2>
  <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
    
  <div class="w-full text-dark flex justify-center items-center space-x-9">
      <div class="w-72 h-32 bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-12 py-4">
        <i class="bi bi-emoji-wink-fill text-4xl"></i>
            <div class="text-semibold mt-2">Kenyamanan Maksimal</div>
      </div>
    </div>

    <div class="w-full text-dark flex justify-center items-center space-x-9">
      <div class="w-72 h-32 bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-12 py-4">
        <i class="bi bi-box-seam-fill text-4xl"></i>
            <div class="text-sm mt-2">Desain Stylish</div>
      </div>
    </div>

    <div class="w-full text-dark flex justify-center items-center space-x-9">
      <div class="w-72 h-32 bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-12 py-4">
        <i class="bi bi-graph-up-arrow text-4xl"></i>
            <div class="text-sm mt-2">Durabilitas Tinggi</div>
      </div>
    </div>

    <div class="w-full text-dark flex justify-center items-center space-x-9">
      <div class="w-72 h-32 bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-12 py-4">
        <i class="bi bi-tags text-4xl"></i>
            <div class="text-sm mt-2">Harga Terjangkau</div>
      </div>
    </div>
  </div>
</section>


<!-- kategori -->
<section class="py-16 lg:px-20 px-4 flex flex-col gap-10">
  <div class="w-full text-start text-xl text-dark">  </div>
  <div class="w-[362px] md:w-full overflow-x-auto">
    <div class="flex w-full">
      <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-yellow-300">High Series</div>
      <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-amber-200">Slip On Series</div>
      <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-yellow-300">Zeus Series</div>
      <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-amber-200"> Ares Series</div>
    </div>
  </div>
</section>


<!-- high -->
<section class="mx-24 my-20">
        <div class="text-2xl mb-10">High Series</div>
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11">
            <div>
                <img src="../assets/series/high-1.png" alt="High 1" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        List Hitam
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 259.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/series/high-2.jpg" alt="High 2" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Hitam - Putih 
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 259.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/series/high-3.jpg" alt="High 3" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Full White
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 259.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/series/high-4.jpg" alt="High 4" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Full Black
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 259.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/series/high-5.jpg" alt="High 5" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        List Hitam - Putih Mono
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 259.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
</section>

<!-- slip -->
<section class="mx-24 my-20">
        <div class="text-2xl mb-10">Slip On Series</div>
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11">
            <div>
                <img src="../assets/slip/on-1.jpg" alt="High 1" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Wave Japan 
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 179.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/slip/on-2.jpg" alt="High 2" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Checkerboard Clasic
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 179.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/slip/on-3.jpg" alt="High 3" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Black Middle White
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 179.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/slip/on-4.jpg" alt="High 4" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                      Stripe Plain black white
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 179.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/slip/on-5.jpg" alt="High 5" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Larva golden dark
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                      Rp 179.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
</section>

<!-- zeus -->
<section class="mx-24 my-20">
        <div class="text-2xl mb-10">Zeus Series</div>
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11">
            <div>
                <img src="../assets/zeus/z-1.jpg" alt="High 1" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Full White 
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 189.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/zeus/z-2.jpg" alt="High 2" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Hitam - Putih
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 189.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/zeus/z-3.jpg" alt="High 3" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Hitam Gem
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 189.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/zeus/z-4.jpg" alt="High 4" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                      Full Black
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 189.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
</section>

<!-- ares -->
<section class="mx-24 my-20">
        <div class="text-2xl mb-10">Ares Series</div>
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11">
            <div>
                <img src="../assets/ares/res-1.jpg" alt="High 1" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                        Army White
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 289.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/ares/res-2.jpg" alt="High 2" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Caramel White
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 289.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/ares/res-3.jpg" alt="High 3" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Off White Stripe
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 289.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/ares/res-4.jpg" alt="High 3" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                       Off White Black
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 289.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <img src="../assets/ares/res-5.jpg" alt="High 4" class="w-52 h-52">
                <div class="bg-yellow-100 p-4">
                    <div class="mb-1">
                      Double B
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 289.000
                        <div class="bg-yellow-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-bag-plus-fill text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
</section>


<!-- testi cus -->
<section class="py-16 lg:px-18 px-4 flex flex-col gap-6 bg-yellow-100">
  <div class="w-full text-center text-xl text-dark mb-9">Testimoni Pelanggan</div>

  <div class="w-full text-dark flex flex-wrap justify-center gap-6">
    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">tisaf</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">kangalu</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">ehyipa</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">yierli</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>
  </div>
</section>


<!-- payment -->
<section class="py-8 lg:py-12 px-4 lg:px-20 flex flex-col gap-10 bg-gray-50">
  <div class="w-full text-start text-xl text-dark"> Metode Pembayaran </div>
  <div class="flex flex-wrap justify-center gap-8">
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/dana.png" alt="metode dana" class="w-24 h-10"></div>
    </div>
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/gopay2.png" alt="metode gopay" class="w-24 h-10"></div>
    </div>
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/bni.png" alt="metode bni" class="w-24 h-10"></div>
    </div>
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/bri.png" alt="metode bri" class="w-24 h-10"></div>
    </div>
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/bca.png" alt="metode bca" class="w-24 h-10"></div>
    </div>
    <div class="bg-white rounded px-8 py-8 cursor-pointer hover:opacity-50">
      <div><img src="../assets/ocbc.png" alt="metode ocbc" class="w-24 h-10"></div>
    </div>
  </div>
</section>


<!-- pertayaan umum -->
<section class="py-8 lg:py-16 px-4 lg:px-20 flex flex-col gap-4 bg-zinc-50">
    <h2 class="text-2xl font-semibold mb-6">Pertanyaan Umum (FAQ)</h2>
    <div class="bg-white border border-gray-300 rounded-lg mb-2">
      <button class="w-full flex justify-between items-center p-4 focus:outline-none">
        <span class="text-lg">lorem ipsum dolor sit amet?</span>
        <i class="bi bi-chevron-down"></i>
      </button>
      <div class="faq-content hidden p-4 text-gray-600">
        lorem lorem
      </div>
    </div>

    <div class="bg-white border border-gray-300 rounded-lg mb-2">
      <button class="w-full flex justify-between items-center p-4 focus:outline-none">
        <span class="text-lg">lorem ipsum dolor sit amet?</span>
        <i class="bi bi-chevron-down"></i>
      </button>
      <div class="faq-content hidden p-4 text-gray-600">
        lorem lorem
      </div>
    </div>

    <div class="bg-white border border-gray-300 rounded-lg mb-2">
      <button class="w-full flex justify-between items-center p-4 focus:outline-none">
        <span class="text-lg">lorem ipsum dolor sit amet?</span>
        <i class="bi bi-chevron-down"></i>
      </button>
      <div class="faq-content hidden p-4 text-gray-600">
        lorem lorem
      </div>
    </div>

    <div class="bg-white border border-gray-300 rounded-lg mb-2">
      <button class="w-full flex justify-between items-center p-4 focus:outline-none">
        <span class="text-lg">lorem ipsum dolor sit amet?</span>
        <i class="bi bi-chevron-down"></i>
      </button>
      <div class="faq-content hidden p-4 text-gray-600">
        lorem lorem
      </div>
    </div>
</section>

<!-- Footer -->
<footer class="text-surface/75 bg-yellow-400 dark:text-white/75 lg:text-left">
  <div class="flex items-center justify-center border-b-2 border-neutral-200 p-6 dark:border-white/10 lg:justify-between">
    <div class="me-12 hidden lg:block">
      <!-- Bungkus gambar dan teks dalam elemen flex -->
      <span class="flex items-center">
        <img src="../assets/logo2.png" alt="Logo" class="w-10 mr-2">
        <span class="text-2xl font-bold">MINUSONE</span>
      </span>
    </div>
  </div>

  <div class="mx-6 py-10">
    <div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
      <!-- Alamat section -->
      <div class="text-left px-4">
        <h6 class="mb-4 font-semibold uppercase">Alamat</h6>
        <p>
          Jl.Kh.Abdul Fatah Hasan
          Warjok
          <br>
          Serang Banten 42117
        </p>
      </div>

      <!-- Produk section -->
      <div class="text-left px-4">
        <h6 class="mb-4 font-semibold uppercase">Produk</h6>
        <p class="mb-4">
          <a href="#!">High Series</a>
        </p>
        <p class="mb-4">
          <a href="#!">Slip On Series</a>
        </p>
        <p class="mb-4">
          <a href="#!">Stroom Series</a>
        </p>
        <p>
          <a href="#!">Clasic Series</a>
        </p>
      </div>

      <!-- Kontak Kami section -->
      <div class="text-left px-4">
        <h6 class="mb-4 font-semibold uppercase">Kontak Kami</h6>
        <p class="mb-4">Serang, Banten, Indonesia</p>
        <p class="mb-4">info@example.com</p>
        <p class="mb-4">+62 234 567 88</p>
      </div>
    </div>
  </div>

  <div class="bg-black/5 p-6 text-center">
    <span class="font-semibold">© 2024 Copyright : </span>
    <a class="font-semibold">MINUSONE</a>
  </div>
</footer>
</template>

