# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>PetVerse – The Ultimate Pet Owners Ecosystem</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #0f172a;
      color: #ffffff;
      overflow-x: hidden;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* ---------- Navbar ---------- */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 24px 8%;
      position: fixed;
      width: 100%;
      top: 0;
      backdrop-filter: blur(10px);
      background: rgba(15, 23, 42, 0.8);
      z-index: 1000;
    }

    .logo {
      font-size: 24px;
      font-weight: 800;
      color: #38bdf8;
    }

    nav a {
      margin-left: 32px;
      font-weight: 500;
      opacity: 0.9;
    }

    nav a:hover {
      color: #38bdf8;
    }

    /* ---------- Hero Section ---------- */
    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      padding: 0 8%;
      background: radial-gradient(circle at top right, #1e293b, #020617);
    }

    .hero-content {
      max-width: 650px;
    }

    .hero h1 {
      font-size: 64px;
      line-height: 1.1;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #38bdf8;
    }

    .hero p {
      font-size: 18px;
      color: #cbd5f5;
      margin-bottom: 32px;
    }

    .hero-buttons {
      display: flex;
      gap: 20px;
    }

    .btn-primary {
      background: #38bdf8;
      color: #020617;
      padding: 14px 28px;
      border-radius: 12px;
      font-weight: 700;
      transition: 0.3s;
    }

    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 30px rgba(56, 189, 248, 0.4);
    }

    .btn-secondary {
      border: 1px solid #38bdf8;
      padding: 14px 28px;
      border-radius: 12px;
      color: #38bdf8;
    }

    /* ---------- Features ---------- */
    .section {
      padding: 100px 8%;
    }

    .section-title {
      text-align: center;
      font-size: 42px;
      margin-bottom: 60px;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 32px;
    }

    .feature-card {
      background: #020617;
      padding: 32px;
      border-radius: 20px;
      border: 1px solid #1e293b;
      transition: 0.3s;
    }

    .feature-card:hover {
      transform: translateY(-8px);
      border-color: #38bdf8;
    }

    .feature-card h3 {
      margin-bottom: 12px;
      color: #38bdf8;
    }

    .feature-card p {
      color: #cbd5f5;
    }

    /* ---------- CTA ---------- */
    .cta {
      text-align: center;
      background: linear-gradient(135deg, #020617, #020617, #0f172a);
      border-radius: 24px;
      padding: 80px 40px;
    }

    .cta h2 {
      font-size: 40px;
      margin-bottom: 20px;
    }

    .cta p {
      color: #cbd5f5;
      margin-bottom: 30px;
    }

    footer {
      text-align: center;
      padding: 40px;
      color: #64748b;
    }

    /* ---------- Responsive ---------- */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 42px;
      }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <header>
    <div class="logo">🐾 PetVerse</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Services</a>
      <a href="#">Community</a>
      <a href="#">Marketplace</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="hero-content">
      <h1>The <span>Ultimate Ecosystem</span> for Pet Owners</h1>
      <p>
        Manage your pet’s health, connect with vets, adopt, shop, and join a global community —
        all in one intelligent platform.
      </p>
      <div class="hero-buttons">
        <a href="#" class="btn-primary">Get Started</a>
        <a href="#" class="btn-secondary">Explore Features</a>
      </div>
    </div>
  </section>

  <!-- Features -->
  <section class="section">
    <h2 class="section-title">Everything Your Pet Needs 🐶🐱</h2>
    <div class="features">
      <div class="feature-card">
        <h3>🩺 Smart Health Records</h3>
        <p>Track vaccinations, medical history, vet visits and reminders in one place.</p>
      </div>

      <div class="feature-card">
        <h3>🏥 Vet Booking</h3>
        <p>Book appointments with verified vets instantly near you.</p>
      </div>

      <div class="feature-card">
        <h3>🛒 Pet Marketplace</h3>
        <p>Buy food, toys, accessories and medicines from trusted sellers.</p>
      </div>

      <div class="feature-card">
        <h3>❤️ Adoption & Rescue</h3>
        <p>Adopt pets or connect with rescue organizations easily.</p>
      </div>

      <div class="feature-card">
        <h3>👥 Community</h3>
        <p>Join pet owners, share stories, tips, and experiences.</p>
      </div>

      <div class="feature-card">
        <h3>🤖 AI Pet Assistant</h3>
        <p>Get instant advice about diet, behavior, and health.</p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="section">
    <div class="cta">
      <h2>Start Your Pet’s Smart Life Today 🚀</h2>
      <p>Join thousands of pet parents using PetVerse to give their pets a better life.</p>
      <a href="#" class="btn-primary">Create Free Account</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 PetVerse. All rights reserved.
  </footer>

</body>
</html>  call.html<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>PetVerse Call System</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Inter, Arial, sans-serif;
}

body {
  background: #0f172a;
  color: white;
}

/* App Layout */
.app {
  max-width: 420px;
  margin: auto;
  height: 100vh;
  background: #020617;
  border-radius: 20px;
  overflow: hidden;
  border: 1px solid #1e293b;
}

/* Header */
.header {
  padding: 16px;
  text-align: center;
  font-weight: 700;
  background: #020617;
  border-bottom: 1px solid #1e293b;
}

/* Contact List */
.contact {
  display: flex;
  align-items: center;
  padding: 14px;
  border-bottom: 1px solid #1e293b;
  cursor: pointer;
}

.contact:hover {
  background: #020617;
}

.avatar {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background: #38bdf8;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  margin-right: 12px;
  color: #020617;
}

.contact-info {
  flex: 1;
}

.call-buttons button {
  background: none;
  border: none;
  color: #38bdf8;
  font-size: 20px;
  margin-left: 10px;
  cursor: pointer;
}

/* Call Screen */
.call-screen {
  display: none;
  flex-direction: column;
  height: 100%;
  justify-content: space-between;
  text-align: center;
  padding: 40px 20px;
}

.call-name {
  font-size: 28px;
  margin-top: 40px;
}

.call-status {
  color: #94a3b8;
  margin-top: 10px;
}

/* Fake Video Area */
.video-box {
  flex: 1;
  background: #020617;
  border-radius: 16px;
  margin: 30px 0;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #64748b;
  font-size: 20px;
}

/* Controls */
.controls {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.control-btn {
  width: 64px;
  height: 64px;
  border-radius: 50%;
  border: none;
  font-size: 22px;
  cursor: pointer;
}

.end {
  background: #ef4444;
  color: white;
}

.accept {
  background: #22c55e;
  color: white;
}

.mute {
  background: #1e293b;
  color: white;
}

/* Ringing */
.ringing {
  animation: pulse 1.2s infinite;
}

@keyframes pulse {
  0% { opacity: 1; }
  50% { opacity: 0.5; }
  100% { opacity: 1; }
}

</style>
</head>
<body>

<div class="app">

  <!-- Contact List -->
  <div id="contactList">
    <div class="header">📞 PetVerse Calls</div>

    <div class="contact">
      <div class="avatar">🐶</div>
      <div class="contact-info">
        <b>Dr. Sharma (Vet)</b><br>
        <small>Online</small>
      </div>
      <div class="call-buttons">
        <button onclick="startCall('Dr. Sharma','audio')">📞</button>
        <button onclick="startCall('Dr. Sharma','video')">📹</button>
      </div>
    </div>

    <div class="contact">
      <div class="avatar">🐱</div>
      <div class="contact-info">
        <b>Pet Community Friend</b><br>
        <small>Online</small>
      </div>
      <div class="call-buttons">
        <button onclick="startCall('Community Friend','audio')">📞</button>
        <button onclick="startCall('Community Friend','video')">📹</button>
      </div>
    </div>
  </div>

  <!-- Call Screen -->
  <div id="callScreen" class="call-screen">
    <div>
      <div class="call-name" id="callName">Calling...</div>
      <div class="call-status ringing" id="callStatus">Ringing...</div>
    </div>

    <div class="video-box" id="videoBox">📹 Video Stream Area</div>

    <div class="controls">
      <button class="control-btn mute">🔇</button>
      <button class="control-btn end" onclick="endCall()">❌</button>
    </div>
  </div>

</div>

<script>
function startCall(name, type) {
  document.getElementById("contactList").style.display = "none";
  document.getElementById("callScreen").style.display = "flex";

  document.getElementById("callName").innerText = name;

  if (type === "audio") {
    document.getElementById("videoBox").innerText = "🎧 Audio Call";
  } else {
    document.getElementById("videoBox").innerText = "📹 Video Call";
  }

  setTimeout(() => {
    document.getElementById("callStatus").innerText = "Connected";
    document.getElementById("callStatus").classList.remove("ringing");
  }, 2000);
}

function endCall() {
  document.getElementById("callScreen").style.display = "none";
  document.getElementById("contactList").style.display = "block";
}
</script>

</body>
</html>