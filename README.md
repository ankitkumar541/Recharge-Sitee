<!-- index.html -->
<!DOCTYPE html>
<html>
<head>
  <title>Recharge Website</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>
  <h1>Welcome to Recharge Site</h1>
  <form>
    <script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_QnjSYKv6Lh9l8c" async></script>
  </form>
  <a href="login.html">Login</a> | <a href="register.html">Register</a>
</body>
</html>

<!-- login.html -->
<!DOCTYPE html>
<html>
<head><title>Login</title></head>
<body>
  <h2>Login</h2>
  <form>
    <input type="text" placeholder="Email">
    <input type="password" placeholder="Password">
    <button type="submit">Login</button>
  </form>
</body>
</html>

<!-- register.html -->
<!DOCTYPE html>
<html>
<head><title>Register</title></head>
<body>
  <h2>Register</h2>
  <form>
    <input type="text" placeholder="Name">
    <input type="email" placeholder="Email">
    <input type="password" placeholder="Password">
    <button type="submit">Register</button>
  </form>
</body>
</html>

<!-- dashboard.html -->
<!DOCTYPE html>
<html>
<head><title>User Dashboard</title></head>
<body>
  <h2>Welcome, User</h2>
  <p>Wallet Balance: ₹1000</p>
  <p>Recharge History:</p>
  <ul>
    <li>01 July: ₹100</li>
    <li>02 July: ₹100</li>
  </ul>
</body>
</html>

<!-- admin/admin_login.html -->
<!DOCTYPE html>
<html>
<head><title>Admin Login</title></head>
<body>
  <h2>Admin Login</h2>
  <form>
    <input type="text" placeholder="Username">
    <input type="password" placeholder="Password">
    <button type="submit">Login</button>
  </form>
</body>
</html>

<!-- admin/admin_dashboard.html -->
<!DOCTYPE html>
<html>
<head><title>Admin Dashboard</title></head>
<body>
  <h2>Admin Panel</h2>
  <p>User List</p>
  <p>Credit Wallet / Monitor Users</p>
</body>
</html>

<!-- scripts/main.js -->
console.log("Main JS loaded");

<!-- scripts/auth.js -->
console.log("Auth JS loaded");

<!-- styles/style.css -->
body { font-family: Arial; background-color: #f2f2f2; padding: 20px; }
