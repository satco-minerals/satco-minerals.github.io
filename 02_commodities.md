---
layout: default
title: Commodities | SATCO
---

<style>
  /* Hero Section */
  .commodities-hero {
    text-align: center;
    margin-bottom: 50px;
  }
  .commodities-hero h2 {
    color: #0d1b2a;
    font-size: 2.2em;
    margin-bottom: 12px;
  }
  .commodities-hero p {
    color: #666;
    max-width: 750px;
    margin: 0 auto;
    line-height: 1.6;
    font-size: 16px;
  }

  /* Grid Layout for 5 Groups */
  .products-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    max-width: 1200px;
    margin: 0 auto 50px auto;
    padding: 0 20px;
  }

  /* Card Style */
  .product-card {
    background: #fff;
    border: 1px solid #e2e8f0;
    border-radius: 8px;
    padding: 25px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.03);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(13, 27, 42, 0.08);
    border-color: #d4af37;
  }

  /* Card Header */
  .card-header {
    display: flex;
    align-items: center;
    gap: 10px;
    border-bottom: 2px solid #f1f5f9;
    padding-bottom: 15px;
    margin-bottom: 15px;
  }
  .card-header .icon {
    font-size: 1.5em;
  }
  .card-header h3 {
    color: #0d1b2a;
    margin: 0;
    font-size: 1.2em;
    font-weight: bold;
  }

  /* Product List Styling */
  .product-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .product-list li {
    margin-bottom: 10px;
    font-size: 14px;
  }
  .product-list a {
    color: #4a5568;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 6px 8px;
    border-radius: 4px;
    transition: all 0.2s;
  }
  .product-list a:hover {
    color: #0d1b2a;
    background: #fdfbf7;
    font-weight: bold;
    padding-left: 12px;
  }
  .product-list a::after {
    content: "→";
    color: #d4af37;
    opacity: 0;
    transition: opacity 0.2s;
  }
  .product-list a:hover::after {
    opacity: 1;
  }

  /* CTA Section */
  .quote-box {
    background: linear-gradient(135deg, #0d1b2a 0%, #1b2a47 100%);
    color: white;
    padding: 35px;
    border-radius: 8px;
    text-align: center;
    max-width: 1160px;
    margin: 40px auto;
    border: 1px solid #d4af37;
  }
</style>

<div class="commodities-hero">
  <h2>Our Commodities Portfolio</h2>
  <p>SATCO is a premium global supplier of industrial minerals, clinker, and construction materials. Click on any product below to view detailed chemical compositions, technical specifications, and packing options.</p>
</div>

<div class="products-grid">

  <!-- CARD 1: CEMENT -->
  <div class="product-card">
    <div class="card-header">
      <span class="icon">🏗️</span>
      <h3>1. Cement Series</h3>
    </div>
    <ul class="product-list">
      <li><a href="#">OPC - Type 1</a></li>
      <li><a href="#">OPC - Type 2</a></li>
      <li><a href="#">OPC - Type 3</a></li>
      <li><a href="#">OPC - Type 4</a></li>
      <li><a href="#">OPC - Type 5</a></li>
      <li><a href="#">White Portland Cement</a></li>
      <li><a href="#">Oil Well Cement</a></li>
      <li><a href="#">Portland Pozzolana (PPC)</a></li>
      <li><a href="#">Special Pozzolanic Cement</a></li>
      <li><a href="#">Composite & Blended Cement</a></li>
      <li><a href="#">Portland Limestone Cement</a></li>
      <li><a href="#">Masonry Cement</a></li>
      <li><a href="#">High Blaine Cement</a></li>
      <li><a href="#">Slag Cement</a></li>
      <li><a href="#">Mixed Cement</a></li>
      <li><a href="#">Advanced Composite Cement</a></li>
    </ul>
  </div>

  <!-- CARD 2: CLINKER -->
  <div class="product-card">
    <div class="card-header">
      <span class="icon">🔥</span>
      <h3>2. Portland Clinker</h3>
    </div>
    <ul class="product-list">
      <li><a href="#">OPC Clinker</a></li>
      <li><a href="#">Low-Alkali Clinker</a></li>
      <li><a href="#">SR Clinker</a></li>
      <li><a href="#">HES Clinker</a></li>
      <li><a href="#">LHC Clinker</a></li>
    </ul>
  </div>

  <!-- CARD 3: GYPSUM -->
  <div class="product-card">
    <div class="card-header">
      <span class="icon">🏔️</span>
      <h3>3. Gypsum Products</h3>
    </div>
    <ul class="product-list">
      <li><a href="#">Natural Gypsum Rock</a></li>
      <li><a href="#">Gypsum Powder</a></li>
    </ul>
  </div>

  <!-- CARD 4: INDUSTRIAL MINERALS -->
  <div class="product-card">
    <div class="card-header">
      <span class="icon">💎</span>
      <h3>4. Industrial Minerals</h3>
    </div>
    <ul class="product-list">
      <li><a href="#">Limestone</a></li>
      <li><a href="#">Calcium Carbonate</a></li>
      <li><a href="#">Dolomite</a></li>
      <li><a href="#">Bentonite</a></li>
      <li><a href="#">Kaolin (China Clay)</a></li>
      <li><a href="#">Barite</a></li>
      <li><a href="#">Fluorspar</a></li>
      <li><a href="#">Feldspar</a></li>
      <li><a href="#">Potash</a></li>
    </ul>
  </div>

  <!-- CARD 5: ECO-ADDITIVES & ENERGY -->
  <div class="product-card">
    <div class="card-header">
      <span class="icon">⚡</span>
      <h3>5. Eco-Additives & Energy</h3>
    </div>
    <ul class="product-list">
      <li><a href="/products/slag.html">Blast Furnace Slag (GGBFS)</a></li>
      <li><a href="#">Microsilica (Silica Fume)</a></li>
      <li><a href="#">Zeolite</a></li>
      <li><a href="#">Coal (Steam & Metallurgical)</a></li>
    </ul>
  </div>

</div>

<!-- CTA Section -->
<div class="quote-box">
  <h3 style="color: #d4af37; margin-top: 0;">Looking for Custom Specifications?</h3>
  <p style="font-size: 15px;">We provide flexible shipping options in Bulk or Jumbo Bags tailored to international maritime standards.</p>
  <a href="/05_contact.html" style="display: inline-block; background: #d4af37; color: #0d1b2a; padding: 12px 25px; text-decoration: none; font-weight: bold; border-radius: 4px; margin-top: 15px; transition: background 0.3s;">Contact Our Trade Desk</a>
</div>
