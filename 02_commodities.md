---
layout: default
title: Commodities | SATCO
---

<style>
  /* Header Section */
  .commodities-hero {
    text-align: center;
    margin-bottom: 40px;
  }
  .commodities-hero h2 {
    color: #0d1b2a;
    font-size: 2em;
    margin-bottom: 10px;
  }
  .commodities-hero p {
    color: #666;
    max-width: 700px;
    margin: 0 auto;
    line-height: 1.6;
  }

  /* Accordion Layout */
  .accordion-wrapper {
    max-width: 950px;
    margin: 0 auto 50px auto;
  }
  .accordion-item {
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 6px;
    margin-bottom: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.02);
    overflow: hidden;
  }
  
  /* Hidden Checkbox for Toggle */
  .accordion-toggle {
    display: none;
  }
  
  /* Accordion Label (Header) */
  .accordion-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 20px;
    background: #0d1b2a;
    color: #fff;
    font-weight: bold;
    font-size: 1.1em;
    cursor: pointer;
    user-select: none;
    transition: background 0.3s;
  }
  .accordion-header:hover {
    background: #15293e;
  }
  .accordion-header .icon {
    font-size: 1.2em;
    transition: transform 0.3s;
    color: #d4af37;
  }

  /* Accordion Content Container */
  .accordion-content {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s ease-out;
    background: #f8f9fa;
  }
  .accordion-body {
    padding: 20px;
  }

  /* Table Styling Inside Accordion */
  .product-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 5px;
    background: #fff;
    border-radius: 4px;
    overflow: hidden;
  }
  .product-table th {
    background: #f1f3f5;
    color: #0d1b2a;
    text-align: left;
    padding: 12px;
    font-weight: bold;
    border-bottom: 2px solid #e0e0e0;
    font-size: 14px;
  }
  .product-table td {
    padding: 12px;
    border-bottom: 1px solid #eee;
    color: #444;
    font-size: 13.5px;
  }
  .product-table tr:last-child td {
    border-bottom: none;
  }
  .product-table tr:hover {
    background: #fdfbf7;
  }

  /* Logic to Open Accordion and Rotate Icon */
  .accordion-toggle:checked ~ .accordion-content {
    max-height: 1200px; /* فضای کافی برای لیست‌های طولانی */
  }
  .accordion-toggle:checked ~ .accordion-header .icon {
    transform: rotate(45deg);
  }
  
  /* Global Quote CTA */
  .quote-box {
    background: linear-gradient(135deg, #0d1b2a 0%, #1b2a47 100%);
    color: white;
    padding: 30px;
    border-radius: 8px;
    text-align: center;
    max-width: 950px;
    margin: 40px auto;
    border: 1px solid #d4af37;
  }
</style>

<div class="commodities-hero">
  <h2>Global Commodities Portfolio</h2>
  <p>SATCO is a strategic sourcing partner supplying high-grade construction materials, clinker, and industrial minerals. Explore our comprehensive portfolio categorized to global trading standards.</p>
</div>

<div class="accordion-wrapper">

  <!-- 1. CEMENT SERIES -->
  <div class="accordion-item">
    <input type="checkbox" id="cat1" class="accordion-toggle" checked>
    <label for="cat1" class="accordion-header">
      <span>🏗️ 1. Comprehensive Cement Series</span>
      <span class="icon">+</span>
    </label>
    <div class="accordion-content">
      <div class="accordion-body">
        <table class="product-table">
          <thead>
            <tr>
              <th>Commercial Name</th>
              <th>Standard / Specification</th>
              <th>Primary Applications</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><strong>Ordinary Portland Cement (OPC Type 1)</strong></td><td>ASTM C150 Type I / EN 197-1 CEM I</td><td>General construction, reinforced concrete, high-strength structures.</td></tr>
            <tr><td><strong>Moderate Sulfate Resistant (Type 2)</strong></td><td>ASTM C150 Type II / EN 197-1</td><td>Structures exposed to moderate sulfate soils or groundwater.</td></tr>
            <tr><td><strong>High Early Strength Cement (Type 3)</strong></td><td>ASTM C150 Type III</td><td>Precast concrete elements, rapid structural operations.</td></tr>
            <tr><td><strong>Low Heat Cement (Type 4)</strong></td><td>ASTM C150 Type IV</td><td>Massive concrete pours, dams, large foundations.</td></tr>
            <tr><td><strong>High Sulfate Resistant Cement (Type 5)</strong></td><td>ASTM C150 Type V / EN 197-1 SR5</td><td>Marine structures, piers, severe sulfate-heavy environments.</td></tr>
            <tr><td><strong>White Portland Cement</strong></td><td>High Whiteness > 90% / Grade 42.5</td><td>Architectural facades, decorative finishes, tile adhesives.</td></tr>
            <tr><td><strong>Oil Well Cement</strong></td><td>API Spec 10A (Class A to H)</td><td>Onshore and offshore oil & gas well cementing.</td></tr>
            <tr><td><strong>Portland Pozzolana Cement (PPC)</strong></td><td>ASTM C595 / EN Blended</td><td>Hydraulic structures, marine work, mass concreting.</td></tr>
            <tr><td><strong>Special Pozzolanic Cement</strong></td><td>High Active Pozzolan Content</td><td>Enhanced durability in harsh, aggressive chemical soils.</td></tr>
            <tr><td><strong>Composite & Blended Cement</strong></td><td>EN 197-1 CEM V</td><td>Eco-friendly infrastructure projects, masonry works.</td></tr>
            <tr><td><strong>Portland Limestone Cement</strong></td><td>EN 197-1 CEM II/A-L</td><td>Finishing works, general structural applications with low carbon footprint.</td></tr>
            <tr><td><strong>Masonry Cement</strong></td><td>ASTM C91 / EN 413-1</td><td>Bricklaying, blockwork, internal and external plastering.</td></tr>
            <tr><td><strong>High Blaine / Ultra Fine Cement</strong></td><td>High Specific Surface Area</td><td>Rapid set repairs, grouting, micro-crack sealing.</td></tr>
            <tr><td><strong>Slag Cement</strong></td><td>EN 197-1 CEM III</td><td>Aggressive chemical zones, low heat structural concrete.</td></tr>
            <tr><td><strong>Mixed Cement</strong></td><td>Custom Blends</td><td>Tailored specific project requirements.</td></tr>
            <tr><td><strong>Advanced Composite Cement</strong></td><td>Multi-Component Matrix</td><td>High durability and optimized compressive strength performance.</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- 2. CLINKER SERIES -->
  <div class="accordion-item">
    <input type="checkbox" id="cat2" class="accordion-toggle">
    <label for="cat2" class="accordion-header">
      <span>🔥 2. Premium Portland Clinker Series</span>
      <span class="icon">+</span>
    </label>
    <div class="accordion-content">
      <div class="accordion-body">
        <table class="product-table">
          <thead>
            <tr>
              <th>Product Grade</th>
              <th>Chemical Profile</th>
              <th>Target Output</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><strong>OPC Clinker</strong></td><td>High C3S Matrix / Standard Alkali</td><td>Base raw material for Ordinary Portland Cement production.</td></tr>
            <tr><td><strong>Low-Alkali Clinker</strong></td><td>Na2O Equivalent &lt; 0.60%</td><td>Mitigates Alkali-Silica Reaction (ASR) in concrete.</td></tr>
            <tr><td><strong>SR Clinker (Sulfate Resistant)</strong></td><td>Low C3A Content (&lt; 5%)</td><td>Essential feedstock for high sulfate-resistant cement grades.</td></tr>
            <tr><td><strong>HES Clinker (High Early Strength)</strong></td><td>Optimized Alite/Belite Phase</td><td>Utilized for fast-setting, high-performance grinding lines.</td></tr>
            <tr><td><strong>LHC Clinker (Low Heat Clinker)</strong></td><td>Controlled Exothermic Profile</td><td>Specifically designed for large-scale mass cement formulas.</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- 3. GYPSUM PRODUCTS -->
  <div class="accordion-item">
    <input type="checkbox" id="cat3" class="accordion-toggle">
    <label for="cat3" class="accordion-header">
      <span>🏔️ 3. Gypsum Minerals</span>
      <span class="icon">+</span>
    </label>
    <div class="accordion-content">
      <div class="accordion-body">
        <table class="product-table">
          <thead>
            <tr>
              <th>Product Type</th>
              <th>Purity & Form</th>
              <th>Primary Industrial Sector</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><strong>Natural Gypsum Rock</strong></td><td>Purity 85% - 95% / Crushed Run</td><td>Setting time regulator for cement grinding plants.</td></tr>
            <tr><td><strong>Gypsum Powder</strong></td><td>Superfine Fine Mesh / Calcined</td><td>Plasterboards, internal wall stucco, architectural moldings.</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- 4. INDUSTRIAL MINERALS -->
  <div class="accordion-item">
    <input type="checkbox" id="cat4" class="accordion-toggle">
    <label for="cat4" class="accordion-header">
      <span>💎 4. Strategic Industrial Minerals</span>
      <span class="icon">+</span>
    </label>
    <div class="accordion-content">
      <div class="accordion-body">
        <table class="product-table">
          <thead>
            <tr>
              <th>Mineral Name</th>
              <th>Processing Form</th>
              <th>Key Markets / Uses</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><strong>Limestone</strong></td><td>Lump / Crushed Aggregate</td><td>Metallurgical flux, steelmaking, aggregate base, lime kiln feed.</td></tr>
            <tr><td><strong>Calcium Carbonate</strong></td><td>Micronized Fine Powder (GCC)</td><td>Filler for paint, plastics, rubber, paper, and coatings.</td></tr>
            <tr><td><strong>Dolomite</strong></td><td>Rock / High Magnesium Powder</td><td>Glassware manufacturing, refractory bricks, ceramics, soil conditioner.</td></tr>
            <tr><td><strong>Bentonite</strong></td><td>Drilling / API Grade & Foundry</td><td>Oil drilling muds, civil engineering pile works, foundry binding.</td></tr>
            <tr><td><strong>Kaolin (China Clay)</strong></td><td>Refined Wash / Powder</td><td>Ceramics, porcelain, paper coating, premium paint fillers.</td></tr>
            <tr><td><strong>Barite</strong></td><td>High SG &ge; 4.20 / API Standard</td><td>Weighting agent for deep high-pressure oil and gas drilling operations.</td></tr>
            <tr><td><strong>Fluorspar</strong></td><td>Acid / Ceramic / Metallurgical Grade</td><td>Steelmaking flux, aluminum production, hydrofluoric acid synthesis.</td></tr>
            <tr><td><strong>Feldspar</strong></td><td>Potassic / Sodic Powder</td><td>Fluxing agent in glass formulation and ceramic body glazes.</td></tr>
            <tr><td><strong>Potash</strong></td><td>Granular / Muriate of Potash (MOP)</td><td>High-yield agricultural fertilizers, chemical industries.</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- 5. ECO-ADDITIVES & ENERGY -->
  <div class="accordion-item">
    <input type="checkbox" id="cat5" class="accordion-toggle">
    <label for="cat5" class="accordion-header">
      <span>⚡ 5. Advanced Eco-Additives & Energy Minerals</span>
      <span class="icon">+</span>
    </label>
    <div class="accordion-content">
      <div class="accordion-body">
        <table class="product-table">
          <thead>
            <tr>
              <th>Product Line</th>
              <th>Physical State</th>
              <th>Industrial Advantage</th>
            </tr>
          </thead>
          <tbody>
            <tr><td><strong>Granulated Blast Furnace Slag (Slag/اسلگ)</strong></td><td>Un-ground Granules / GGBS Feed</td><td>Partial replacement of cement to maximize concrete durability.</td></tr>
            <tr><td><strong>Microsilica (Silica Fume)</strong></td><td>Densified / Undensified Gray Powder</td><td>Essential for high-strength concrete, reducing porosity.</td></tr>
            <tr><td><strong>Zeolite</strong></td><td>Natural Porous Crystals / Powder</td><td>Water filtration, gas purification, agricultural soil moisture retainers.</td></tr>
            <tr><td><strong>Coal (ذغال سنگ)</strong></td><td>Steam & Metallurgical Bituminous</td><td>Thermal energy source for cement kilns, power utilities, and steel industries.</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

</div>

<!-- CTA Section -->
<div class="quote-box">
  <h3 style="color: #d4af37; margin-top: 0;">Request Technical Data Sheets (TDS) or Commercial Quotes</h3>
  <p style="font-size: 14px;">SATCO offers flexible logistics networks across maritime and land channels. We provide custom chemical specifications packed in Bulk or 1.5 MT Jumbo Bags tailored to your destination port.</p>
  <a href="/05_contact.html" style="display: inline-block; background: #d4af37; color: #0d1b2a; padding: 12px 25px; text-decoration: none; font-weight: bold; border-radius: 4px; margin-top: 15px;">Contact Our Global Trade Desk</a>
</div>
