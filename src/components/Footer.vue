<template>
    <footer class="footer">
      <div class="container">
        <div class="footer-section">
          <h3>Download Now</h3>
          <!-- Add your download link or buttons here -->
        </div>
        <div class="footer-section">
          <h3>License</h3>
          <!-- Add license information or links here -->
        </div>
        <div class="footer-section">
          <h3>About</h3>
          <!-- Add information about your company here -->
        </div>
        <div class="footer-section">
          <h3>Pricing</h3>
          <!-- Add pricing information or links here -->
        </div>
        <div class="footer-section">
          <h3>Careers</h3>
          <!-- Add career information or links here -->
        </div>
        <div class="footer-section">
          <h3>Help</h3>
          <!-- Add help or support information here -->
        </div>
        <div class="footer-section">
          <h3>Privacy Policy</h3>
          <!-- Add privacy policy information or links here -->
        </div>
      </div>
      <div class="footer-bottom">
        <p>2020 Landify UI kit. All rights reserved.</p>
        <p>For any help, please contact us: +855-81640732 | <a href="mailto:www@WeFresh.com">www@WeFresh.com</a></p>
        <p><a href="#">Get the App</a></p>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer'
  }
  </script>
  
  <style scoped>
  .footer {
    padding: 50px;
    background-color: #0b1015;
    text-align: center;
  }
  .footer-section {
    margin-bottom: 20px;
  }
  .footer-bottom {
    border-top: 1px solid #e9ecef;
    padding-top: 20px;
  }
  a {
    color: #007bff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  </style>