---
layout: default
title: Commodities | SATCO
---

<style>
  .commodities-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
  }
  /* استایل باکسِ گروه */
  .category-box {
    background: #0d1b2a;
    border: 3px solid #d4af37;
    border-radius: 12px;
    padding: 20px;
    text-align: center;
    color: #d4af37;
    font-weight: 800;
    text-transform: uppercase;
    font-size: 1.1em;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    margin-top: 15px;
  }
  /* استایل باکسِ محصول (ست با گروه) */
  .product-item {
    background: #0d1b2a;
    border: 2px solid #d4af37;
    color: #ffffff;
    padding: 6px 14px;
    border-radius: 6px;
    font-size: 0.85em;
    text-decoration: none;
    transition: 0.3s;
  }
  .product-item:hover {
    background: #d4af37;
    color: #0d1b2a;
    border-color: #ffffff;
  }
</style>

<div class="commodities-container">
  <div class="category-box">BASE CEMENT SERIES
    <div class="product-list">
      <a href="/products/opc-type1/" class="product-item">Type 1</a>
      <a href="/products/opc-type2/" class="product-item">Type 2</a>
      <a href="/products/opc-type3/" class="product-item">Type 3</a>
      <a href="/products/opc-type4/" class="product-item">Type 4</a>
      <a href="/products/opc-type5/" class="product-item">Type 5</a>
    </div>
  </div>

  <div class="category-box">PORTLAND CLINKER
    <div class="product-list">
      <a href="/products/OPC-Clinker/" class="product-item">OPC</a>
      <a href="/products/low-alkali-clinker/" class="product-item">Low-Alkali</a>
      <a href="/products/sr-clinker/" class="product-item">SR</a>
      <a href="/products/hes-clinker/" class="product-item">HES</a>
      <a href="/products/lhc-clinker/" class="product-item">LHC</a>
    </div>
  </div>

  <div class="category-box">GYPSUM PRODUCTS
    <div class="product-list">
      <a href="/products/gypsum-mineral/" class="product-item">Rock</a>
      <a href="/products/gypsum-powder/" class="product-item">Powder</a>
    </div>
  </div>

  <div class="category-box">SPECIALIZED CEMENT
    <div class="product-list">
      <a href="/products/white-portland-cement/" class="product-item">White</a>
      <a href="/products/oil-well-cement/" class="product-item">Oil Well</a>
      <a href="/products/portland-pozzolan-cement/" class="product-item">PPC</a>
      <a href="/products/special-pozzolanic-cement/" class="product-item">Special</a>
      <a href="/products/blended-cements/" class="product-item">Blended</a>
      <a href="/products/limestone-portland-cement/" class="product-item">Limestone</a>
      <a href="/products/masonry-cement/" class="product-item">Masonry</a>
      <a href="/products/high-blaine-cement/" class="product-item">High Blaine</a>
      <a href="/products/slag-cement/" class="product-item">Slag</a>
      <a href="/products/calcium-aluminate-cement/" class="product-item">Calcium Aluminate</a>
      <a href="/products/portland-composite-cement/" class="product-item">Composite</a>
    </div>
  </div>

  <div class="category-box">INDUSTRIAL MINERALS
    <div class="product-list">
      <a href="/products/limestone/" class="product-item">Limestone</a>
      <a href="/products/calcium-carbonate/" class="product-item">CaCO3</a>
      <a href="/products/dolomite/" class="product-item">Dolomite</a>
      <a href="/products/bentonite/" class="product-item">Bentonite</a>
      <a href="/products/kaolin/" class="product-item">Kaolin</a>
      <a href="/products/barite/" class="product-item">Barite</a>
      <a href="/products/fluorspar/" class="product-item">Fluorspar</a>
      <a href="/products/feldspar/" class="product-item">Feldspar</a>
      <a href="/products/potash/" class="product-item">Potash</a>
    </div>
  </div>

  <div class="category-box">ECO-ADDITIVES & ENERGY
    <div class="product-list">
      <a href="/products/blast-furnace-slag/" class="product-item">Slag</a>
      <a href="/products/microsilica/" class="product-item">Microsilica</a>
      <a href="/products/zeolite/" class="product-item">Zeolite</a>
      <a href="/products/coal/" class="product-item">Coal</a>
    </div>
  </div>
</div>
