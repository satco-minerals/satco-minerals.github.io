---
layout: default
title: SATCO | Global Commodities & Supply Chain Partner
---

<style>
  .page-header {
    background-image: url('Banner.png') !important;
    background-size: cover !important;
    background-position: center !important;
  }

  /* Navigation Bar Styling */
  .custom-nav {
    background: #1a252f;
    padding: 15px 5px;
    text-align: center;
    border-radius: 4px;
    margin-bottom: 30px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
  }
  .custom-nav a {
    color: #fff !important;
    text-decoration: none;
    font-weight: bold;
    font-size: 14px;
    cursor: pointer;
    padding: 5px 10px;
    border-bottom: 2px solid transparent;
    transition: 0.3s;
  }
  .custom-nav a:hover, .dropdown:hover .dropbtn {
    border-bottom: 2px solid #cc7a00;
  }
  
  /* Dropdown General */
  .dropdown { display: inline-block; position: relative; }
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 200px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 100;
    text-align: left;
    border-radius: 4px;
    margin-top: 10px;
  }
  .dropdown-content a {
    color: #333 !important;
    padding: 10px 16px;
    display: block;
    margin: 0;
    font-weight: normal;
    border-bottom: none !important;
  }
  .dropdown-content a:hover { background-color: #f1f1f1; }
  .dropdown:hover > .dropdown-content { display: block; }

  /* Nested Dropdown Logic */
  .dropdown-submenu { position: relative; }
  .dropdown-submenu .dropdown-content {
    display: none; /* مخفی ماندن در حالت پیش‌فرض */
    top: 0; 
    left: 100%; 
    margin-top: -10px;
  }
  .dropdown-submenu:hover > .dropdown-content { display: block; } /* فقط با هاور روی Cement نمایش داده شود */

  /* Product Grid */
  .product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  .product-card {
    background: #f8f9fa;
    padding: 15px;
    border-left: 4px solid #cc7a00;
    border-radius: 4px;
    font-weight: bold;
  }
</style>

<nav class="custom-nav">
  <a href="index.html">Home</a>
  <a href="about.html">About Us</a>
  
  <div class="dropdown">
    <a class="dropbtn">Minerals ▾</a>
    <div class="dropdown-content">
      <div class="dropdown-submenu">
        <a href="#">Cement ‣</a>
        <div class="dropdown-content">
          <a href="cement-type1.html">Type 1</a>
          <a href="cement-type2.html">Type 2</a>
          <a href="cement-type3.html">Type 3</a>
          <a href="cement-type4.html">Type 4</a>
          <a href="cement-type5.html">Type 5</a>
          <a href="cement-drill.html">Drilling Cement</a>
          <a href="cement-white.html">White Cement</a>
          <a href="cement-pozzolanic.html">Pozzolanic</a>
        </div>
      </div>
      <a href="#">Clinker</a>
      <a href="#">Dolomite</a>
      <a href="#">Gypsum Stone & Powder</a>
      <a href="#">Microsilica</a>
      <a href="#">Calcium Carbonate</a>
    </div>
  </div>

  <div class="dropdown">
    <a class="dropbtn">Petrochemicals ▾</a>
    <div class="dropdown-content">
      <a href="#">Bitumen</a>
      <a href="#">Urea</a>
      <a href="#">Methanol</a>
      <a href="#">Polyethylene</a>
      <a href="#">Polypropylene</a>
      <a href="#">PVC</a>
      <a href="#">Acetic Acid</a>
      <a href="#">MEG</a>
    </div>
  </div>

  <div class="dropdown">
    <a class="dropbtn">Refined ▾</a>
    <div class="dropdown-content">
      <a href="#">Sulfur</a>
      <a href="#">Gas Oil / Diesel</a>
      <a href="#">Base Oil</a>
      <a href="#">Fuel Oil / Mazut</a>
      <a href="#">LPG</a>
    </div>
  </div>
  
  <a href="#">Logistics Consulting</a>
  <a href="contact.html">Contact Us</a>
</nav>

<div style="text-align: center; margin: 40px 0;">
  <p style="font-size: 1.2em; color: #555;">
    Expert in International Logistics, Commodity Sourcing, and Strategic Consulting. <br>
    We deliver reliable commodities directly to your destination with professional logistics management.
  </p>
  <a href="contact.html" class="btn" style="background-color: #cc7a00; color: white; padding: 10px 20px; text-decoration: none; border-radius: 4px; display: inline-block; margin-top: 15px;">Request a Quote</a>
</div>

<hr>

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
