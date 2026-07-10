---
layout: default
title: Commodities | SATCO
---

<style>
  .commodities-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
    padding: 60px 20px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .category-box {
    background: #0d1b2a;
    border: 3px solid #d4af37;
    border-radius: 15px;
    padding: 40px 20px;
    text-align: center;
    color: white;
    font-weight: 800;
    text-transform: uppercase;
    font-size: 1.5em;
    min-height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    transition: 0.3s;
  }
  .category-box:hover {
    background: #1b263b;
    transform: scale(1.03);
    border-color: #fff;
  }
</style>

<div class="commodities-container">
  <a href="/products/base-cement/" class="category-box">BASE CEMENT SERIES</a>
  <a href="/products/clinker/" class="category-box">PORTLAND CLINKER</a>
  <a href="/products/gypsum/" class="category-box">GYPSUM PRODUCTS</a>
  <a href="/products/special-cement/" class="category-box">SPECIALIZED CEMENT</a>
  <a href="/products/minerals/" class="category-box">INDUSTRIAL MINERALS</a>
  <a href="/products/eco-energy/" class="category-box">ECO-ADDITIVES & ENERGY</a>
</div>
