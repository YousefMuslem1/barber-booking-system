<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Barber Booking System</title>
  <style>
    /* Basic styling for the README */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      background: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    pre {
      background: #ecf0f1;
      padding: 10px;
      border-radius: 4px;
      overflow-x: auto;
    }
    code {
      font-family: Consolas, monospace;
    }
    ul {
      margin-left: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    table, th, td {
      border: 1px solid #bdc3c7;
    }
    th, td {
      padding: 8px;
      text-align: left;
    }
    .section {
      margin-bottom: 30px;
    }
  </style>
</head>
<body>
  <div class="section">
    <h1>Barber Booking System ✂️</h1>
    <p>
      A full-featured web application for managing a barbershop, built with Laravel (API backend) and Vue 3 (frontend SPA). 
      This project includes a powerful permission system, user management, services, bookings, and more.
    </p>
  </div>

  <div class="section">
    <h2>Tech Stack</h2>
    <ul>
      <li><strong>Backend:</strong> Laravel 10, Laravel Sanctum, Spatie Laravel Permission</li>
      <li><strong>Frontend:</strong> Vue 3, Vite, Pinia, Tailwind CSS</li>
      <li><strong>Auth:</strong> Token-based authentication</li>
      <li><strong>Other:</strong> PDF Export, Dynamic Roles/Permissions, Responsive UI</li>
    </ul>
  </div>

  <div class="section">
    <h2>How to Run the Project</h2>
    <h3>Backend (Laravel API)</h3>
    <pre><code>
cd barber-booking-api
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
    </code></pre>
    <h3>Frontend (Vue 3)</h3>
    <pre><code>
cd barber-booking-frontend
npm install
npm run dev
    </code></pre>
    <p>Make sure to update the API base URL in the frontend configuration if needed.</p>
  </div>

  <div class="section">
    <h2>Features</h2>
    <ul>
      <li>User Authentication (Login / Roles / Permissions)</li>
      <li>Staff Management</li>
      <li>Service Management</li>
      <li>Booking System (with filters, status control, and export features)</li>
      <li>Dynamic Role & Permission Assignment (Admin Panel)</li>
      <li>Protected Routes & UI Elements based on Permissions</li>
    </ul>
  </div>

  <div class="section">
    <h2>Test Accounts</h2>
    <table>
      <tr>
        <th>Role</th>
        <th>Email</th>
        <th>Password</th>
      </tr>
      <tr>
        <td>Admin</td>
        <td>admin@example.com</td>
        <td>password</td>
      </tr>
      <tr>
        <td>Staff</td>
        <td>staff@example.com</td>
        <td>password</td>
      </tr>
    </table>
  </div>

  <div class="section">
    <h2>Screenshots</h2>
    <p>Screenshots can be added later.</p>
  </div>

  <div class="section">
    <h2>License</h2>
    <p>This project is open-source and free to use.</p>
  </div>
</body>
</html>
