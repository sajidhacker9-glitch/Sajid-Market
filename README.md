<!doctype html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sajid's Marketplace — Fresh Fruits & Pro Editing</title>
  <meta name="description" content="Sajid's Marketplace — Fresh fruits delivered in Pakistan. Professional photo & video editing services. Contact: tffaforextrade@gmail.com" />
  <meta property="og:title" content="Sajid's Marketplace" />
  <meta property="og:description" content="Fresh fruits delivered + Professional editing services. Contact on Instagram: @ffwithsajid" />
  <meta property="og:image" content="https://source.unsplash.com/1200x630/?mango" />
  <link rel="icon" href="/favicon.ico" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root{--brand-green:#16a34a;--brand-blue:#0ea5e9}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
  </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased">

  <!-- NAVBAR -->
  <header class="sticky top-0 z-40 bg-white/80 backdrop-blur-md border-b">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <div class="flex items-center gap-4">
          <a href="#home" class="flex items-center gap-3">
            <img src="https://source.unsplash.com/64x64/?mango,fruit" alt="logo" class="w-10 h-10 rounded-md object-cover" loading="lazy">
            <div>
              <div class="text-lg font-bold">Sajid's Marketplace</div>
              <div class="text-xs text-gray-500">Fresh Fruits • Pro Editing</div>
            </div>
          </a>
        </div>

        <nav class="hidden md:flex items-center gap-6">
          <a class="nav-link text-sm font-medium text-gray-700 hover:text-black" href="#products">Products</a>
          <a class="nav-link text-sm font-medium text-gray-700 hover:text-black" href="#services">Services</a>
          <a class="nav-link text-sm font-medium text-gray-700 hover:text-black" href="#pricing">Price List</a>
          <a class="nav-link text-sm font-medium text-gray-700 hover:text-black" href="#testimonials">Reviews</a>
          <a class="nav-link text-sm font-medium text-gray-700 hover:text-black" href="#contact">Contact</a>
        </nav>

        <div class="flex items-center gap-3">
          <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="hidden sm:inline-flex items-center gap-2 px-3 py-2 rounded-md bg-[#f5f5f5] hover:bg-[#f1f1f1] border">
            <svg class="w-5 h-5 text-pink-600" viewBox="0 0 24 24" fill="currentColor"><path d="M7.75 2h8.5A5.75 5.75 0 0 1 22 7.75v8.5A5.75 5.75 0 0 1 16.25 22h-8.5A5.75 5.75 0 0 1 2 16.25v-8.5A5.75 5.75 0 0 1 7.75 2zM12 7.1A4.9 4.9 0 1 0 12 17.9 4.9 4.9 0 0 0 12 7.1zM18.5 6.2a1.1 1.1 0 1 0 0 2.2 1.1 1.1 0 0 0 0-2.2z"/></svg>
            <span class="text-sm">@ffwithsajid</span>
          </a>

          <button id="cartBtn" class="relative inline-flex items-center px-3 py-2 rounded-md bg-green-600 text-white hover:bg-green-700">
            Cart <span id="cartCount" class="ml-2 inline-block bg-white text-green-700 px-2 py-0.5 rounded-full text-xs">0</span>
          </button>

          <button id="mobileMenuBtn" class="md:hidden inline-flex items-center p-2 rounded-md bg-gray-100">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div id="mobileMenu" class="hidden md:hidden border-t bg-white">
      <div class="px-4 pt-4 pb-6 space-y-2">
        <a href="#products" class="block py-2">Products</a>
        <a href="#services" class="block py-2">Services</a>
        <a href="#pricing" class="block py-2">Price List</a>
        <a href="#contact" class="block py-2">Contact</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <main id="home">
    <section class="relative bg-gradient-to-br from-white to-green-50 overflow-hidden">
      <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-16 lg:py-24 grid lg:grid-cols-2 gap-8 items-center">
        <div>
          <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 leading-tight">Fresh Fruits Delivered to Your Doorstep<br><span class="text-green-600">&</span> Professional Photo & Video Editing</h1>
          <p class="mt-4 text-lg text-gray-600 max-w-xl">Farm fresh mangoes, apples, grapes, and custom editing packages for creators and businesses. Fast delivery across Pakistan.</p>

          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#products" class="inline-flex items-center px-5 py-3 bg-green-600 text-white rounded-lg shadow hover:bg-green-700">Shop Fruits</a>
            <a href="#services" class="inline-flex items-center px-5 py-3 border rounded-lg">Get Editing Services</a>
            <a href="#contact" class="inline-flex items-center px-5 py-3 border rounded-lg">Contact Us</a>
          </div>

          <div class="mt-8 flex gap-4 items-center text-sm text-gray-600">
            <div class="flex items-center gap-2">
              <svg class="w-6 h-6 text-green-500" viewBox="0 0 24 24" fill="currentColor"><path d="M2 3h20v2H2zM2 19h20v2H2zM10 7h4v10h-4z"/></svg>
              <div>
                <div class="font-semibold">Free delivery</div>
                <div class="text-xs">On orders above Rs. 1000</div>
              </div>
            </div>

            <div class="flex items-center gap-2">
              <svg class="w-6 h-6 text-blue-500" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2a7 7 0 0 0-7 7v4h14V9a7 7 0 0 0-7-7zM5 20h14v-2H5z"/></svg>
              <div>
                <div class="font-semibold">Secure Orders</div>
                <div class="text-xs">Email: tffaforextrade@gmail.com</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Hero media: image + video preview -->
        <div class="space-y-4">
          <div class="rounded-2xl overflow-hidden shadow-lg">
            <img src="https://source.unsplash.com/800x600/?mango,fruit" alt="mango" class="w-full h-64 object-cover" loading="lazy">
          </div>

          <div class="rounded-2xl overflow-hidden shadow-lg bg-black">
            <video id="promoVideo" controls class="w-full h-56 object-cover bg-black" preload="none">
              <source src="/assets/mango-promo.mp4" type="video/mp4">
              Your browser does not support video.
            </video>
          </div>
        </div>
      </div>
    </section>

    <!-- PRODUCTS -->
    <section id="products" class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <div class="flex items-center justify-between mb-6">
        <h2 class="text-2xl font-bold">Our Fresh Fruits</h2>
        <div class="text-sm text-gray-500">Showing popular items</div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <!-- product card template -->
        <template id="product-template">
          <div class="bg-white rounded-xl shadow p-4 flex flex-col">
            <img class="product-img w-full h-44 object-cover rounded-md mb-3" loading="lazy">
            <h3 class="product-title font-semibold text-lg"></h3>
            <p class="product-price text-green-600 font-bold mt-1"></p>
            <div class="mt-auto flex items-center gap-2">
              <div class="flex items-center border rounded-md overflow-hidden">
                <button class="qty-decrease px-3 py-1">-</button>
                <input class="qty-input w-12 text-center" value="1" inputmode="numeric">
                <button class="qty-increase px-3 py-1">+</button>
              </div>
              <button class="add-to-cart px-4 py-2 bg-green-600 text-white rounded-md">Add</button>
            </div>
          </div>
        </template>
      </div>
    </section>

    <!-- PRICE LIST -->
    <section id="pricing" class="bg-white border-t py-10">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-2xl font-bold mb-4">Price List (per kg)</h2>
        <div class="overflow-x-auto">
          <table class="w-full table-auto text-left border-collapse">
            <thead class="bg-gray-100">
              <tr>
                <th class="py-3 px-4">Fruit</th>
                <th class="py-3 px-4">Price</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border-b">
                <td class="py-3 px-4">Kinnow Orange</td>
                <td class="py-3 px-4">Rs. 250/kg</td>
              </tr>
              <tr class="border-b">
                <td class="py-3 px-4">White Chaunsa Mango</td>
                <td class="py-3 px-4">Rs. 270/kg</td>
              </tr>
              <tr class="border-b">
                <td class="py-3 px-4">Fajri Mango</td>
                <td class="py-3 px-4">Rs. 190/kg</td>
              </tr>
              <tr class="border-b">
                <td class="py-3 px-4">Peach</td>
                <td class="py-3 px-4">Rs. 300-320/kg</td>
              </tr>
              <tr class="border-b">
                <td class="py-3 px-4">Plum (Aalu Bukhara)</td>
                <td class="py-3 px-4">Rs. 360/kg</td>
              </tr>
              <tr class="border-b">
                <td class="py-3 px-4">Banana</td>
                <td class="py-3 px-4">Rs. 190/dozen</td>
              </tr>
              <tr>
                <td class="py-3 px-4">Kiwi (Imported)</td>
                <td class="py-3 px-4">Rs. 500/kg</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <h2 class="text-2xl font-bold mb-4">Editing & Creative Services</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-xl shadow">
          <h3 class="font-semibold text-lg">Basic Photo Edit</h3>
          <p class="text-sm text-gray-600 mt-2">Color correction, crop, basic retouch.</p>
          <div class="mt-4 font-bold">Rs. 300 / image</div>
        </div>
        <div class="bg-white p-6 rounded-xl shadow">
          <h3 class="font-semibold text-lg">Pro Video Edit</h3>
          <p class="text-sm text-gray-600 mt-2">Cuts, color grade, captions, music sync.</p>
          <div class="mt-4 font-bold">Rs. 800 / minute</div>
        </div>
        <div class="bg-white p-6 rounded-xl shadow">
          <h3 class="font-semibold text-lg">AI Style/3D</h3>
          <p class="text-sm text-gray-600 mt-2">Stylized AI conversions (Ghibli/3D/Cartoon).</p>
          <div class="mt-4 font-bold">Custom Pricing</div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials" class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <h2 class="text-2xl font-bold mb-6">What customers say</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <blockquote class="bg-white p-6 rounded-xl shadow">
          <div class="flex items-center gap-3 mb-3">
            <img src="https://source.unsplash.com/64x64/?person" alt="user" class="w-12 h-12 rounded-full object-cover">
            <div>
              <div class="font-semibold">Ali R.</div>
              <div class="text-xs text-gray-500">Verified Buyer</div>
            </div>
          </div>
          <p class="text-gray-600">"Fresh mangoes and quick delivery. Editing work was professional. Highly recommended!"</p>
        </blockquote>

        <blockquote class="bg-white p-6 rounded-xl shadow">
          <div class="flex items-center gap-3 mb-3">
            <img src="https://source.unsplash.com/64x64/?man" alt="user" class="w-12 h-12 rounded-full object-cover">
            <div>
              <div class="font-semibold">Sara K.</div>
              <div class="text-xs text-gray-500">Content Creator</div>
            </div>
          </div>
          <p class="text-gray-600">"Their video editing turned my raw clips into a viral short. Great value."</p>
        </blockquote>

        <blockquote class="bg-white p-6 rounded-xl shadow">
          <div class="flex items-center gap-3 mb-3">
            <img src="https://source.unsplash.com/64x64/?woman" alt="user" class="w-12 h-12 rounded-full object-cover">
            <div>
              <div class="font-semibold">Hamid S.</div>
              <div class="text-xs text-gray-500">Bulk Buyer</div>
            </div>
          </div>
          <p class="text-gray-600">"Best prices for bulk mango orders. Excellent customer service."</p>
        </blockquote>
      </div>
    </section>

    <!-- FAQ -->
    <section class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <h2 class="text-2xl font-bold mb-4">FAQs</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <details class="bg-white p-4 rounded-lg shadow">
          <summary class="font-semibold">What are the delivery charges?</summary>
          <p class="mt-2 text-gray-600">Free delivery on orders above Rs. 1000. For smaller orders, delivery charges apply depending on location.</p>
        </details>
        <details class="bg-white p-4 rounded-lg shadow">
          <summary class="font-semibold">How long does editing take?</summary>
          <p class="mt-2 text-gray-600">Basic photo edits: 24 hours. Pro video edits: 2-4 days depending on length.</p>
        </details>
        <details class="bg-white p-4 rounded-lg shadow">
          <summary class="font-semibold">How to place bulk orders?</summary>
          <p class="mt-2 text-gray-600">Contact us on Instagram or WhatsApp with your requirement and we'll provide a custom quote.</p>
        </details>
        <details class="bg-white p-4 rounded-lg shadow">
          <summary class="font-semibold">Payment methods?</summary>
          <p class="mt-2 text-gray-600">Cash on Delivery, Bank Transfer, or via WhatsApp order confirmation.</p>
        </details>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="bg-gradient-to-b from-white to-gray-50 py-12 border-t">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="bg-white rounded-xl shadow p-6 md:flex md:items-center md:justify-between gap-6">
          <div>
            <h3 class="text-xl font-bold">Get in touch</h3>
            <p class="text-gray-600 mt-1">Email: <a href="mailto:tffaforextrade@gmail.com" class="text-blue-600">tffaforextrade@gmail.com</a></p>
            <p class="text-gray-600 mt-1">Instagram: <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="text-pink-600">@ffwithsajid</a></p>
          </div>

          <div class="flex items-center gap-3">
            <a id="whatsappBtn" href="#" class="inline-flex items-center px-4 py-3 bg-green-600 text-white rounded-lg shadow">Message on WhatsApp</a>
            <a href="mailto:tffaforextrade@gmail.com" class="inline-flex items-center px-4 py-3 border rounded-lg">Email Us</a>
          </div>
        </div>

        <p class="mt-3 text-sm text-gray-500">Note: Replace the placeholder WhatsApp number in the code with your number (with country code, e.g., 9234xxxxxxx).</p>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="mt-10 bg-white border-t">
      <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex flex-col sm:flex-row items-center justify-between gap-4">
        <div class="text-sm text-gray-600">© 2025 Sajid's Marketplace. All rights reserved.</div>
        <div class="flex items-center gap-4">
          <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="text-pink-600">Instagram</a>
          <a href="#" class="text-gray-600">Privacy</a>
          <a href="#" class="text-gray-600">Terms</a>
        </div>
      </div>
    </footer>
  </main>

  <!-- CART DRAWER -->
  <div id="cartDrawer" class="fixed right-4 bottom-4 w-80 bg-white rounded-xl shadow-lg p-4 hidden">
    <h4 class="font-bold mb-2">Your Cart</h4>
    <div id="cartItems" class="space-y-2 max-h-48 overflow-auto"></div>
    <div class="mt-3 flex items-center justify-between">
      <div class="font-semibold">Total:</div>
      <div id="cartTotal" class="font-bold">Rs. 0</div>
    </div>
    <div class="mt-3 flex gap-2">
      <button id="checkoutBtn" class="flex-1 px-3 py-2 bg-green-600 text-white rounded">Checkout</button>
      <button id="clearCartBtn" class="px-3 py-2 border rounded">Clear</button>
    </div>
  </div>

  <script>
    // --- Sample products data (replace with your real data or JSON) ---
    const products = [
      {id:1, title:'White Chaunsa Mango', price:270, img:'https://source.unsplash.com/600x400/?chaunsa,mango'},
      {id:2, title:'Fajri Mango', price:190, img:'https://source.unsplash.com/600x400/?fajri,mango'},
      {id:3, title:'Kinnow Orange', price:250, img:'https://source.unsplash.com/600x400/?kinnow,orange'},
      {id:4, title:'Apple (Kala Kulu)', price:220, img:'https://source.unsplash.com/600x400/?apple'},
      {id:5, title:'Banana (Dozen)', price:190, img:'https://source.unsplash.com/600x400/?banana'},
      {id:6, title:'Grapes (Green)', price:350, img:'https://source.unsplash.com/600x400/?grapes'}
    ];

    // render products
    const container = document.querySelector('#products > div.grid');
    const template = document.getElementById('product-template');
    products.forEach(p=>{
      const clone = template.content.cloneNode(true);
      clone.querySelector('.product-img').src = p.img;
      clone.querySelector('.product-title').textContent = p.title;
      clone.querySelector('.product-price').textContent = 'Rs. '+p.price;
      const qtyInput = clone.querySelector('.qty-input');
      const inc = clone.querySelector('.qty-increase');
      const dec = clone.querySelector('.qty-decrease');
      inc.addEventListener('click', ()=> qtyInput.value = Number(qtyInput.value)+1);
      dec.addEventListener('click', ()=> { if(Number(qtyInput.value)>1) qtyInput.value = Number(qtyInput.value)-1 });
      clone.querySelector('.add-to-cart').addEventListener('click', (e)=>{
        addToCart(p.id, Number(qtyInput.value));
      });
      container.appendChild(clone);
    });

    // CART LOGIC using localStorage
    let cart = JSON.parse(localStorage.getItem('sajid_cart')||'[]');
    const cartBtn = document.getElementById('cartBtn');
    const cartDrawer = document.getElementById('cartDrawer');
    const cartCount = document.getElementById('cartCount');
    const cartItemsEl = document.getElementById('cartItems');
    const cartTotalEl = document.getElementById('cartTotal');

    function saveCart(){ localStorage.setItem('sajid_cart', JSON.stringify(cart)); renderCart(); }
    function addToCart(id, qty){
      const prod = products.find(p=>p.id===id);
      const found = cart.find(i=>i.id===id);
      if(found) found.qty += qty; else cart.push({id:id, title:prod.title, price:prod.price, qty:qty});
      saveCart();
      showDrawer();
    }

    function renderCart(){
      cartItemsEl.innerHTML='';
      let total=0; cart.forEach(item=>{
        const row = document.createElement('div'); row.className='flex items-center justify-between';
        row.innerHTML = `<div class="text-sm"><div class="font-semibold">${item.title}</div><div class="text-xs text-gray-500">Qty: ${item.qty}</div></div><div class="text-sm font-semibold">Rs. ${item.price*item.qty}</div>`;
        cartItemsEl.appendChild(row);
        total += item.price*item.qty;
      });
      cartCount.textContent = cart.reduce((s,i)=>s+i.qty,0);
      cartTotalEl.textContent = 'Rs. '+total;
    }

    function showDrawer(){ cartDrawer.classList.remove('hidden'); }
    document.getElementById('clearCartBtn').addEventListener('click', ()=>{cart=[]; saveCart();});
    cartBtn.addEventListener('click', ()=>{ cartDrawer.classList.toggle('hidden'); });
    document.getElementById('checkoutBtn').addEventListener('click', ()=>{
      if(cart.length===0){ alert('Cart is empty'); return; }
      // generate whatsapp message
      const phone = 'YOUR_WHATSAPP_NUMBER'; // REPLACE WITH: 923XXXXXXXXX (country code +92)
      let msg = `New order from website:%0A`;
      cart.forEach(it=>{ msg += `${it.title} - Qty: ${it.qty} - Rs.${it.price*it.qty}%0A` });
      msg += `Total: ${cart.reduce((s,i)=>s+i.price*i.qty,0)}%0A`;
      msg += `Customer Email: tffaforextrade@gmail.com`;
      const url = `https://wa.me/${phone}?text=${msg}`;
      window.open(url, '_blank');
    });

    // initial render
    renderCart();

    // mobile menu
    document.getElementById('mobileMenuBtn').addEventListener('click', ()=>{ document.getElementById('mobileMenu').classList.toggle('hidden'); });

    // smooth active link highlight
    const navLinks = document.querySelectorAll('.nav-link');
    function onScroll(){
      const pos = window.scrollY + 120;
      document.querySelectorAll('main section[id]').forEach(sec=>{
        if(sec.offsetTop <= pos && (sec.offsetTop + sec.offsetHeight) > pos){
          navLinks.forEach(a=> a.classList.remove('text-black','font-bold'));
          const target = Array.from(navLinks).find(a=> a.getAttribute('href') === '#'+sec.id);
          if(target){ target.classList.add('text-black','font-bold'); }
        }
      });
    }
    window.addEventListener('scroll', onScroll);

    // small performance tips: images have loading="lazy" and we use source.unsplash placeholders
  </script>

</body>
</html>
