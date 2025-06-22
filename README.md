<!DOCTYPE html>
<html lang="en">
<head>    
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sowrov Website</title>
 <style>
  /* ৩ ডট মেনু ডিজাইন */
  .menu-box {
    position: absolute;
    top: 20px;
    right: 20px;
  }
  .dots {
    font-size: 24px;
    cursor: pointer;
  }
  .dropdown {
    display: none;
    position: absolute;
    right: 0;
    background: #fff;
    border: 1px solid #ccc;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    z-index: 10;
  }
  .dropdown a {
    display: block;
    padding: 10px 15px;
    text-decoration: none;
    color: #000;
  }
  .dropdown a:hover {
    background-color: #f0f0f0;
  } 
  st    body {
      font-family: Arial, sans-serif;
      background: #f0f8ff;
      text-align: center;
      padding-top: 100px;
    }
    h1 {
      color: #1e90ff;
    }
    p {
      font-size: 18px;
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    img {
      margin-top: 20px;
      border-radius: 10px;
      width: 200px;
    }
  </style>
</head>
<body>
  <h1>Welcome to Sowrov's Website</h1>
  <p>📞 Contact: 01606672228</p>
  <p>🔗 <a href="https://www.facebook.com/share/18HrYmE8oo/">Facebook Profile</a><p>
  <p>WhatsApp: <a href="https://wa.me/8801606672228" target="_blank">মেসেজ পাঠাও</a></p>
  <img src="https://uploads.onecompiler.io/43nf3b8nx/43nf3kxby/3075.jpg" alt="Sowrov's Photo" />
  <marquee direction="left" scrollamount="4" style="color: green; font-size: 22px;">
  আমার প্রথম ওয়েবসাইটে স্বাগতম
</marquee>
<script>
  function toggleMenu() {
    const m = document.getElementById("menu");
    m.style.display = m.style.display === "block" ? "none" : "block";
  }
  window.onclick = e => {
    if (!e.target.matches('.dots')) {
      document.getElementById("menu").style.display = "none";
    }
  };
  <script>
  function toggleMenu() {
    const m = document.getElementById("menu");
    m.style.display = m.style.display === "block" ? "none" : "block";
  }
  window.onclick = e => {
    if (!e.target.matches('.dots')) {
      document.getElementById("menu").style.display = "none";
    }
  };
</script>

<!-- 
  📌 নির্দেশনা:

  - এই পেইজে marquee ট্যাগ দিয়ে "Welcome to my first website" লেখা চলন্ত আকারে যুক্ত করা হয়েছে।
  - ডান পাশে ⋮ বাটন (3-dot menu) যুক্ত হয়েছে, যাতে Home, About, Projects, Contact লিংক আছে।
  - বাইরে ক্লিক করলে মেনু অটো বন্ধ হয়।
-->
</body>
</html>
