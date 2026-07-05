---
layout: default
title: Contact Us | SATCO
---

<style>
  /* Page Layout */
  .contact-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
    margin-top: 30px;
  }
  
  /* WhatsApp Button */
  .whatsapp-btn {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #25D366;
    color: white !important;
    padding: 15px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
    margin-bottom: 25px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: background 0.3s;
  }
  .whatsapp-btn:hover {
    background-color: #128C7E;
  }
  
  /* Form Styling */
  .contact-form {
    background: #f8f9fa;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    border-top: 4px solid #cc7a00;
  }
  .form-group {
    margin-bottom: 20px;
  }
  .form-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
    color: #1a252f;
  }
  .form-group input, .form-group select, .form-group textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    font-family: inherit;
  }
  .form-group textarea {
    resize: vertical;
    height: 120px;
  }
  .submit-btn {
    background-color: #cc7a00;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    font-weight: bold;
    cursor: pointer;
    width: 100%;
    transition: background 0.3s;
  }
  .submit-btn:hover {
    background-color: #b36b00;
  }

  /* Info Details */
  .info-item {
    margin-bottom: 25px;
  }
  .info-item h4 {
    color: #cc7a00;
    margin-bottom: 5px;
    font-size: 1.1em;
  }
  .info-item p {
    color: #555;
    margin: 0;
    line-height: 1.6;
  }
</style>

<h2>Get in Touch</h2>
<p style="color: #666;">Have an immediate inquiry or need a strategic sourcing partner? Reach out to our global team.</p>

<div class="contact-container">
  
  <!-- Left Column: WhatsApp & Form -->
  <div>
    <!-- Direct WhatsApp Link -->
    <a href="https://wa.me/971502905700" target="_blank" class="whatsapp-btn">
      Chat Directly on WhatsApp
    </a>

    <!-- Smart Inquiry Form -->
    <div class="contact-form">
      <form action="https://formspree.io/f/xwvdlygn" method="POST">
        <div class="form-group">
          <label for="name">Full Name *</label>
          <input type="text" id="name" name="name" required placeholder="John Doe">
        </div>
        <div class="form-group">
          <label for="company">Company Name (Optional)</label>
          <input type="text" id="company" name="company" placeholder="Your Company Ltd.">
        </div>
        <div class="form-group">
          <label for="email">Email Address *</label>
          <input type="email" id="email" name="_replyto" required placeholder="john@example.com">
        </div>
        <div class="form-group">
          <label for="inquiry_type">Inquiry Type *</label>
          <select id="inquiry_type" name="inquiry_type" required>
            <option value="" disabled selected>Select an option</option>
            <option value="Commodities">Commodities Sourcing</option>
            <option value="Logistics">Logistics & Supply Chain</option>
            <option value="Other">Other Inquiries</option>
          </select>
        </div>
        <div class="form-group">
          <label for="message">Your Message *</label>
          <textarea id="message" name="message" required placeholder="Please describe your requirements, specifications, or volume..."></textarea>
        </div>
        <button type="submit" class="submit-btn">Send Inquiry</button>
      </form>
    </div>
  </div>

  <!-- Right Column: Contact Details & Hours -->
  <div style="padding-top: 10px;">
    <div class="info-item">
      <h4>Direct Contact</h4>
      <p><strong>Email:</strong> Satco.group1998@gmail.com</p>
      <p><strong>Phone / WhatsApp:</strong> +971 50 290 5700</p>
    </div>
    <div class="info-item">
      <h4>Business Hours (Dubai Time)</h4>
      <p>Monday - Friday: 8:00 AM - 6:00 PM (GMT+4)</p>
      <p>24/7 Operations Support for Active Cargo & Logistics</p>
    </div>
  </div>

</div>
