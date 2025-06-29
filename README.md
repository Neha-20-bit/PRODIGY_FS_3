<h1>🛍️ Local Store E-Commerce Platform</h1>
<p>A complete responsive e-commerce website designed for local stores. Customers can browse products, add to cart, checkout securely, and track orders. Built using <strong>HTML, CSS, JavaScript, PHP, and MySQL</strong>.</p>

<hr>

<h2>🌟 Features</h2>
<ul>
  <li>🖼️ Product Listings with images, prices & descriptions</li>
  <li>🛒 Shopping Cart functionality</li>
  <li>💳 Checkout process with order placement</li>
  <li>📦 Order Tracking system</li>
  <li>📬 Customer Support Contact Form</li>
  <li>⭐ Optional: User Reviews</li>
  <li>🔍 Sort & Filter products by price</li>
</ul>

<hr>

<h2>🖥️ Demo</h2>
<p><em>To see a live preview, deploy it on XAMPP or your preferred hosting environment.</em></p>
<pre><code>http://localhost/Local-store-E-commerce-platform-main/index.html</code></pre>

<hr>

<h2>🗂️ Project Structure</h2>
<pre><code>Local-store-E-commerce-platform-main/
├── index.html
├── cart.html
├── checkout.html
├── track.html
├── contact.html
├── product.html
├── styles/
│   └── styles.css
├── scripts/
│   └── script.js
├── backend/
│   ├── db.php
│   ├── get-products.php
│   ├── add-to-cart.php
│   ├── place-order.php
│   ├── track-order.php
│   ├── submit-review.php
│   └── contact-form.php
├── images/
│   └── sample-product.jpg
├── data/
│   └── database.sql
└── README.md</code></pre>

<hr>

<h2>🧰 Tech Stack</h2>
<table>
  <tr>
    <th>Layer</th>
    <th>Tools</th>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>HTML, CSS, JavaScript</td>
  </tr>
  <tr>
    <td>Backend</td>
    <td>PHP</td>
  </tr>
  <tr>
    <td>Database</td>
    <td>MySQL</td>
  </tr>
  <tr>
    <td>Server</td>
    <td>XAMPP / WAMP</td>
  </tr>
</table>

<hr>

<h2>🚀 Getting Started</h2>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/yourusername/Local-store-E-commerce-platform-main.git</code></pre>

<h3>2. Move to XAMPP's htdocs</h3>
<pre><code>mv Local-store-E-commerce-platform-main C:/xampp/htdocs/</code></pre>

<h3>3. Import Database</h3>
<ul>
  <li>Start Apache and MySQL via XAMPP</li>
  <li>Go to <code>http://localhost/phpmyadmin</code></li>
  <li>Create a new database: <code>ecommerce</code></li>
  <li>Import <code>data/database.sql</code></li>
</ul>

<h3>4. Configure db.php</h3>
<pre><code>// backend/db.php
$conn = mysqli_connect("localhost", "root", "", "ecommerce");</code></pre>

<h3>5. Run the Application</h3>
<pre><code>http://localhost/Local-store-E-commerce-platform-main/index.html</code></pre>

<hr>

<h2>📄 License</h2>
<p>This project is free to use for educational and non-commercial purposes. Attribution is appreciated.</p>

<hr>

<h2>🤝 Contributing</h2>
<p>Pull requests are welcome! If you'd like to contribute, feel free to fork the repository and submit a PR.</p>

<hr>

<p><strong>Built with ❤️ to support small & local businesses.</strong></p>

</body>
</html>
