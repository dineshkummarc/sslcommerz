<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>SSLCommerz Payment Gateway Integration</h1>
<p>A project for integrating the SSLCommerz payment gateway with your application.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#features">Features</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#configuration">Configuration</a></li>
    <li><a href="#examples">Examples</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
</ul>

<h2 id="features">Features</h2>
<ul>
    <li>Easy payment processing via SSLCommerz.</li>
    <li>Supports various currencies and payment methods.</li>
</ul>

<h2 id="installation">Installation</h2>
<pre><code>1. Clone the repository:
git clone https://github.com/nazrulislam-CSE/sslcommerz.git

2. Install dependencies:
composer install

3. Configure environment variables:
cp .env.example .env
</code></pre>

<h2 id="usage">Usage</h2>
<p>Run the application with:</p>
<pre><code>php artisan serve</code></pre>

<h2 id="configuration">Configuration</h2>
<p>Ensure SSLCommerz credentials are added in the environment file:</p>
<pre><code>SSL_STORE_ID=your_store_id
SSL_STORE_PASSWORD=your_store_password
SSL_SANDBOX=true
</code></pre>

<h2 id="examples">Examples</h2>
<p>Example of a payment initiation:</p>
<pre><code>// Controller function
public function initiatePayment(Request $request) {
    $payment = new SslCommerz();
    return $payment->initiate([...]);
}</code></pre>

<h2 id="contributing">Contributing</h2>
<ul>
    <li>Fork the repository</li>
    <li>Create a branch (<code>git checkout -b feature-name</code>)</li>
    <li>Commit your changes</li>
    <li>Push the branch and create a pull request</li>
</ul>

<h2 id="license">License</h2>
<p>This project is licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</p>

<h2 id="contact">Contact</h2>
<ul>
    <li>Email: <a href="mailto:nsuzon02@gmail.com">nsuzon02@gmail.com</a></li>
    <li>GitHub Repository: <a href="https://github.com/nazrulislam-CSE/sslcommerz">https://github.com/nazrulislam-CSE/sslcommerz</a></li>
</ul>

</body>
</html>
