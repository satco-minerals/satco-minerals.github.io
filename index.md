---
layout: default
title: SATCO | Global Commodities & Supply Chain Partner
---

<!-- استایل اختصاصی برای درست کردن منو، چیدمان و بنر سفارشی بالا -->
<style>
  /* کد حذف کادر سبز و جایگزینی بنر بندرگاه و کالاها */
  .page-header {
    background-image: url('Banner.png') !important;
    background-size: cover !important;
    background-position: center !important;
  }

  .custom-nav {
    background: #1a252f;
    padding: 15px;
    text-align: center;
    border-radius: 4px;
    margin-bottom: 30px;
  }
  .custom-nav a {
    color: #fff !important;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
  }
  .dropdown {
    display: inline-block;
    position: relative;
  }
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 180px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    text-align: left;
    border-radius: 4px;
  }
  .dropdown-content a {
    color: #333 !important;
    padding: 12px 16px;
    display: block;
    margin: 0;
    border-bottom: 1px solid #eee;
  }
  .dropdown-content a:hover { background-color: #f1f1f1; }
  .dropdown:hover .dropdown-content { display: block; }
  
  .product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  .product-card {
    background: #f8f9fa;
    padding: 15px;
    border-left: 4px solid #cc7a00; /* رنگ مسی ساتکو */
    border-radius: 4px;
    font-weight: bold;
  }
</style>

<!-- ۱. انتقال منو به بالای صفحه با ویژگی کشویی برای کالاها -->
<nav class="custom-nav">
  <a href="#">Home</a>
  <a href="#">About Us</a>
  <div class="dropdown">
    <a href="#" class="dropbtn">Commodities ▾</a>
    <div class="dropdown-content">
      <a href="#">Cement</a>
      <a href="#">Clinker</a>
      <a href="#">Dolomite</a>
      <a href="#">Gypsum Stone</a>
      <a href="#">Gypsum Powder</a>
      <a href="#">Microsilica</a>
      <a href="#">Calcium Carbonate</a>
    </div>
  </div>
  <a href="#">Logistics Consulting</a>
  <a href="#">Contact Us</a>
</nav>

<!-- ۲. بخش معرفی اصلی -->
<div style="text-align: center; margin: 40px 0;">
  <p style="font-size: 1.2em; color: #555;">
    Expertise in International Logistics, Commodity Sourcing, and Strategic Consulting. <br>
    We deliver reliable commodities directly to your destination with professional logistics management.
  </p>
  <a href="#" class="btn" style="background-color: #cc7a00; color: white; padding: 10px 20px; text-decoration: none; border-radius: 4px; display: inline-block; margin-top: 15px;">Request a Quote</a>
</div>

<hr>

<!-- ۳. نمایش محصولات به صورت باکس‌های شیک به جای لیست زیر هم -->
<h3>Our Core Products</h3>
<div class="product-grid">
  <div class="product-card">Cement</div>
  <div class="product-card">Clinker</div>
  <div class="product-card">Dolomite</div>
  <div class="product-card">Gypsum Stone</div>
  <div class="product-card">Gypsum Powder</div>
  <div class="product-card">Microsilica / Silica Fume</div>
  <div class="product-card">Calcium Carbonate</div>
</div>
