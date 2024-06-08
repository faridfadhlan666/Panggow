# Tampilan Website
![image](https://github.com/faridfadhlan666/Panggow/assets/162896380/6f263d2a-644e-4e05-a14e-ea8a8afe5730)
![image](https://github.com/faridfadhlan666/Panggow/assets/162896380/30d0d841-bacf-48e0-a95b-0084d3cf7fca)
![image](https://github.com/faridfadhlan666/Panggow/assets/162896380/429cb84a-eb95-498b-95ff-edf2abf9b239)


# Website Panggow

Pangsit Gowreng adalah website promosi dan penjualan produk pangsit goreng terenak dan termurah se-Bogor. Website ini memiliki fitur pencarian produk dengan kata kunci untuk memudahkan pengguna menemukan produk yang mereka inginkan.

## Fitur

- **Tampilan Promosi:** Menampilkan deskripsi dan promosi produk Pangsit Gowreng.
- **Formulir Pencarian:** Memungkinkan pengguna mencari produk dengan kata kunci.
- **Hasil Pencarian Dinamis:** Menampilkan hasil pencarian produk yang sesuai dengan kata kunci yang dimasukkan.

## Teknologi yang Digunakan

- HTML
- CSS
- JavaScript

## Struktur Proyek

```plaintext
.
├── index.html
├── css
│   └── styles.css
└── js
    └── script.js
```

## Cara Menggunakan

1. **Clone Repository**

   ```sh
   git clone https://github.com/faridfadhlan666/pangsit-gowreng.git
   cd pangsit-gowreng
   ```

2. **Buka `index.html` di Browser**

   Buka file `index.html` di browser pilihan Anda untuk melihat tampilan website.

## Kode Utama

### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Panggow</title>
</head>

<body>
    <!-- PENGUMUMAN -->
    <div class="bg-rose-600 px-4 py-3 text-white">
        <p class="text-center text-sm font-medium">
            PROMO GRAND OPENING, CUMA Rp. 10.000!
            <a href="#" class="inline-block underline">Berlaku untuk hari ini aja!</a>
        </p>
    </div>
    <!-- END PENGUMUMAN -->

    <!-- NAVBAR -->
    <header>
        <div class="mx-auto max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8">
            <div class="sm:flex sm:items-center sm:justify-between">
                <div class="text-center sm:text-left">
                    <img src="Group 1.png" style="height: 50px; width: auto" />

                    <p class="mt-1.5 text-sm text-gray-500">
                        Pangsit Gowreng dengan sejuta kenikmatan! 🎉
                    </p>
                </div>

                <div class="mt-4 flex flex-col gap-4 sm:mt-0 sm:flex-row sm:items-center">
                    <a href="cara belanja.html"
                        class="inline-flex items-center justify-center gap-1.5 rounded-lg border border-gray-200 bg-white px-5 py-3 text-gray-500 transition hover:text-gray-700 focus:outline-none focus:ring"
                        type="button">
                        <span class="text-sm font-medium"> Cara Belanja </span>

                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14" />
                        </svg>
                    </a>

                    <a href="https://wa.me/628871178260?text=Halo MinGow, saya mau order Panggownya dong!"
                        class="block rounded-lg bg-rose-600 px-5 py-3 text-sm font-medium text-white transition hover:bg-indigo-700 focus:outline-none focus:ring"
                        type="button">
                        Chat Admin
                    </a>
                </div>
            </div>
        </div>
    </header>
    <!-- END NAVBAR-->

    <!-- CALL TO ACTION -->
    <section class="bg-gray-50">
        <div class="p-8 md:p-12 lg:px-16 lg:py-24">
            <div class="mx-auto max-w-lg text-center">
                <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">
                    Pangsit Gowreng Terenak & Termurah Se-Bogor!
                </h2>

                <p class="hidden text-gray-500 sm:mt-4 sm:block">
                    Produk Homemade, dengan bahan pilihan dan tanpa pengawet apapun!
                    Dijamin enak pastinya.
                </p>
            </div>

            <div class="mx-auto mt-8 max-w-xl">
                <form id="search-form" class="sm:flex sm:gap-4">
                    <div class="sm:flex-1">
                        <input id="search-input" type="text" placeholder="Pangsit Gowreng + Saus Pedas..."
                            class="w-full rounded-md border-gray-200 bg-white p-3 text-gray-700 shadow-sm transition focus:border-white focus:outline-none focus:ring focus:ring-rose-400" />
                    </div>

                    <button type="submit"
                        class="group mt-4 flex w-full items-center justify-center gap-2 rounded-md bg-rose-600 px-5 py-3 text-white transition focus:outline-none focus:ring focus:ring-indigo-400 sm:mt-0 sm:w-auto">
                        <span class="text-sm font-medium"> Cari Produk </span>

                        <svg class="size-5 rtl:rotate-180" xmlns="http://www.w3.org/2000/svg" fill="none"
                            viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M17 8l4 4m0 0l-4 4m4-4H3" />
                        </svg>
                    </button>
                </form>
            </div>
        </div>
    </section>
    <!-- END CALL TO ACTION -->

    <!-- PRODUCT LIST -->
    <div id="product-list" class="container grid grid-cols-3 gap-4 max-w-l mx-auto py-8">
        <a href="https://wa.me/628871178260?text=Halo MinGow, saya mau order Panggow + Saus Pedasnya dong!"
            class="group block product-item">
            <img src="https://plus.unsplash.com/premium_photo-1673769108070-580fe90b8de7?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="" class="aspect-square w-full rounded object-cover" />

            <div class="mt-3">
                <h3 class="font-medium text-gray-900 group-hover:underline group-hover:underline-offset-4">
                    Panggow + Saus Pedas
                </h3>

                <p class="mt-1 text-sm text-gray-700">Rp. 10.000</p>
            </div>
        </a>
        <a href="https://wa.me/628871178260?text=Halo MinGow, saya mau order Panggow + Mayonaisenya dong!"
            class="group block product-item">
            <img src="https://plus.unsplash.com/premium_photo-1673769108070-580fe90b8de7?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="" class="aspect-square w-full rounded object-cover" />

            <div class="mt-3">
                <h3 class="font-medium text-gray-900 group-hover:underline group-hover:underline-offset-4">
                    Panggow + Mayonaise
                </h3>

                <p class="mt-1 text-sm text-gray-700">Rp. 10.000</p>
            </div>
        </a>
        <a href="https://wa.me/628871178260?text=Halo MinGow, saya mau order Panggow + Saus Mentainya dong!"
            class="group block product-item">
            <img src="https://plus.unsplash.com/premium_photo-1673769108070-580fe90b8de7?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="" class="aspect-square w-full rounded object-cover" />

            <div class="mt-3">
                <h3 class="font-medium text-gray-900 group-hover:underline group-hover:underline-offset-4">
                    Panggow + Saus Mentai
                </h3>

                <p class="mt-1 text-sm text-gray-700">Rp. 10.000</p>
            </div>
        </a>
    </div>
    <!-- END PRODUCT LIST -->

    <!-- FOOTER -->
    <footer class="bg-gray-50">
        <div class="mx-auto max-w-screen-xl px-4 py-8 sm:px-6 lg:px-8">
            <div class="sm:flex sm:items-center sm:justify-between">
                <div class="flex justify-center text-rose-600 sm:justify-start font-bold">
                    Panggow
                </div>

                <p class="mt-4 text-center text-sm text-gray-500 lg:mt-0 lg:text-right">
                    Copyright &copy; 2024. All rights reserved.
                </p>
            </div>
        </div>
    </footer>
    <!-- END FOOTER -->

    <!-- JavaScript -->
    <script>
        document.getElementById('search-form').addEventListener('submit', function(event) {
            event.preventDefault();
            const query = document.getElementById('search-input').value.toLowerCase();
            const products = document.querySelectorAll('.product-item');

            products.forEach(product => {
                const productName = product.querySelector('h3').textContent.toLowerCase();
                if (productName.includes(query)) {
                    product.style.display = 'block';
                } else {
                    product.style.display = 'none';
                }
            });
        });
    </script>
</body>

</html>
```

### HTML (cara_belanja.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Cara belanja di Panggow</title>
</head>
<body>
    <!-- PENGUMUMAN -->
    <div class="bg-rose-600 px-4 py-3 text-white">
            <p class="text-center text-sm font-medium">
              PROMO GRAND OPENING, CUMA Rp. 10.000!
              <a href="#" class="inline-block underline">Berlaku untuk hari ini aja!</a>
            </p>
    </div>
    <!-- END PENGUMUMAN -->
    
    <!-- NAVBAR -->
    <header>
        <div class="mx-auto max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8">
          <div class="sm:flex sm:items-center sm:justify-between">
            <div class="text-center sm:text-left">
                <a href="index.html">
                    <img src="Group 1.png" style="height: 50px; width: auto;" alt="Deskripsi Gambar">
                </a>
                
      
              <p class="mt-1.5 text-sm text-gray-500">Pangsit Gowreng dengan sejuta kenikmatan! 🎉</p>
            </div>
      
            <div class="mt-4 flex flex-col gap-4 sm:mt-0 sm:flex-row sm:items-center">
              <button
                class="inline-flex items-center justify-center gap-1.5 rounded-lg border border-gray-200 bg-white px-5 py-3 text-gray-500 transition hover:text-gray-700 focus:outline-none focus:ring"
                type="button"
              >
                <span class="text-sm font-medium"> Cara Belanja </span>
      
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-4 w-4"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                  />
                </svg>
              </button>
      
              <button
                class="block rounded-lg bg-rose-600 px-5 py-3 text-sm font-medium text-white transition hover:bg-indigo-700 focus:outline-none focus:ring"
                type="button"
              >
                Chat Admin
              </button>
            </div>
          </div>
        </div>
    </header>
    <!-- END NAVBAR -->

    <!-- CONTENT -->
    <div class="space-y-4 px-4">
        <details class="group [&_summary::-webkit-details-marker]:hidden" open>
          <summary
            class="flex cursor-pointer items-center justify-between gap-1.5 rounded-lg bg-gray-50 p-4 text-gray-900"
          >
            <h2 class="font-medium">Bagaimana cara membeli produk?</h2>
      
            <svg
              class="size-5 shrink-0 transition duration-300 group-open:-rotate-180"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
            </svg>
          </summary>
      
          <p class="mt-4 px-4 leading-relaxed text-gray-700">
            Pilih produk yang tersedia di halaman beranda website, lalu klik. Setelah itu anda akan diarahkan langsung ke nomor whatsapp admin kami.
          </p>
        </details>
      
        <details class="group [&_summary::-webkit-details-marker]:hidden">
          <summary
            class="flex cursor-pointer items-center justify-between gap-1.5 rounded-lg bg-gray-50 p-4 text-gray-900"
          >
            <h2 class="font-medium">Bagaimana cara klaim diskon?</h2>
      
            <svg
              class="size-5 shrink-0 transition duration-300 group-open:-rotate-180"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
            </svg>
          </summary>
      
          <p class="mt-4 px-4 leading-relaxed text-gray-700">
            Sertakan kode promo "PANGGOW5RIBU" ketika hendak berbelanja via chat whatsapp.
          </p>
        </details>
      </div>
    <!-- END CONTENT -->
</body>
</html>

### CSS (css/styles.css)

```css
/* Tambahkan CSS sesuai kebutuhan */
```

### JavaScript (js/script.js)

```javascript
const products = [
  "Pangsit Gowreng + Saus Pedas",
  "Pangsit Gowreng + Mentai",
  "Pangsit Gowreng + Keju",
  "Pangsit Gowreng Original"
];

document.getElementById('search-form').addEventListener('submit', function(event) {
  event.preventDefault();
  const query = document.getElementById('search-input').value.toLowerCase();
  const results = products.filter(product => product.toLowerCase().includes(query));
  
  const resultsContainer = document.getElementById('results');
  resultsContainer.innerHTML = '';
  if (results.length > 0) {
    results.forEach(product => {
      const resultItem = document.createElement('div');
      resultItem.textContent = product;
      resultsContainer.appendChild(resultItem);
    });
  } else {
    resultsContainer.textContent = 'Tidak ada produk yang ditemukan';
  }
});
```

## Kontribusi

Silakan buat _pull request_ untuk kontribusi pada proyek ini. Setiap kontribusi sangat dihargai!

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

Dengan README ini, pengguna dan kontributor akan mendapatkan pemahaman yang jelas tentang proyek Anda, cara menggunakannya, dan bagaimana mereka dapat berkontribusi.
