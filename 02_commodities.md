---
layout: default
title: Commodities | SATCO
---

<style>
  .commodities-hero { text-align: center; margin-bottom: 50px; padding: 20px; }
  .commodities-hero h2 { color: #0d1b2a; font-size: 2.5em; margin-bottom: 10px; }
  
  /* گرید اصلی برای ۳۶ محصول */
  .commodities-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 20px;
    max-width: 1100px;
    margin: 0 auto 60px auto;
    padding: 0 20px;
  }

  /* استایل باکس صنعتی (حس کیسه/جامبوبگ) */
  .product-box {
    height: 160px;
    background: #ffffff;
    border: 2px dashed #cbd5e1;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 15px;
    text-decoration: none;
    color: #0d1b2a;
    font-weight: 700;
    font-size: 1.1em;
    text-align: center;
    transition: all 0.3s ease;
    position: relative;
  }

  .product-box:hover {
    background: #0d1b2a;
    color: #d4af37;
    border: 2px solid #d4af37;
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }

  .product-box::before {
    content: "SATCO";
    position: absolute;
    top: 10px;
    font-size: 0.6em;
    letter-spacing: 2px;
    opacity: 0.3;
  }

  .quote-box {
    background: #0d1b2a;
    color: white;
    padding: 40px;
    border-radius: 8px;
    text-align: center;
    max-width: 900px;
    margin: 20px auto;
    border: 1px solid #d4af37;
  }
</style>

<div class="commodities-hero">
  <h2>Our Commodities Portfolio</h2>
  <p>Standardized industrial supply chain. Click on any product to view technical specifications.</p>
</div>

<div class="commodities-grid">
  <a href="#" class="product-box">OPC - Type 1</a>
  <a href="#" class="product-box">OPC - Type 2</a>
  <a href="#" class="product-box">OPC - Type 3</a>
  <a href="#" class="product-box">OPC - Type 4</a>
  <a href="#" class="product-box">OPC - Type 5</a>
  <a href="#" class="product-box">White Portland Cement</a>
  <a href="#" class="product-box">Oil Well Cement</a>
  <a href="#" class="product-box">Portland Pozzolana (PPC)</a>
  <a href="#" class="product-box">Special Pozzolanic Cement</a>
  <a href="#" class="product-box">Composite & Blended Cement</a>
  <a href="#" class="product-box">Portland Limestone Cement</a>
  <a href="#" class="product-box">Masonry Cement</a>
  <a href="#" class="product-box">High Blaine Cement</a>
  <a href="#" class="product-box">Slag Cement</a>
  <a href="#" class="product-box">Mixed Cement</a>
  <a href="#" class="product-box">Advanced Composite Cement</a>

  <a href="#" class="product-box">OPC Clinker</a>
  <a href="#" class="product-box">Low-Alkali Clinker</a>
  <a href="#" class="product-box">SR Clinker</a>
  <a href="#" class="product-box">HES Clinker</a>
  <a href="#" class="product-box">LHC Clinker</a>

  <a href="#" class="product-box">Natural Gypsum Rock</a>
  <a href="#" class="product-box">Gypsum Powder</a>

  <a href="#" class="product-box">Limestone</a>
  <a href="#" class="product-box">Calcium Carbonate</a>
  <a href="#" class="product-box">Dolomite</a>
  <a href="#" class="product-box">Bentonite</a>
  <a href="#" class="product-box">Kaolin (China Clay)</a>
  <a href="#" class="product-box">Barite</a>
  <a href="#" class="product-box">Fluorspar</a>
  <a href="#" class="product-box">Feldspar</a>
  <a href="#" class="product-box">Potash</a>

  <a href="/products/slag.html" class="product-box">Blast Furnace Slag</a>
  <a href="#" class="product-box">Microsilica</a>
  <a href="#" class="product-box">Zeolite</a>
  <a href="#" class="product-box">Coal</a>
</div>

<div class="quote-box">
  <h3 style="color: #d4af37; margin-top: 0;">Looking for Custom Specifications?</h3>
  <p>We provide flexible shipping options in Bulk or Jumbo Bags tailored to international maritime standards.</p>
  <a href="/05_contact.html" style="display: inline-block; background: #d4af37; color: #0d1b2a; padding: 12px 25px; text-decoration: none; font-weight: bold; border-radius: 4px; margin-top: 15px;">Contact Our Trade Desk</a>
</div>
