#
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GusdurPoint</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(135deg, #3b2b8f, #5f3dc4);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  background: white;
  width: 90%;
  max-width: 400px;
  padding: 30px;
  border-radius: 25px;
  text-align: center;
  box-shadow: 0 15px 40px rgba(0,0,0,0.2);
}

h1 {
  margin: 0;
  font-size: 24px;
}

.subtitle {
  color: gray;
  font-size: 14px;
  margin-bottom: 25px;
}

.tab {
  display: flex;
  background: #eee;
  border-radius: 15px;
  overflow: hidden;
  margin-bottom: 20px;
}

.tab button {
  flex: 1;
  padding: 10px;
  border: none;
  background: transparent;
  font-weight: bold;
}

.tab .active {
  background: linear-gradient(135deg, #5f3dc4, #7950f2);
  color: white;
}

input {
  width: 100%;
  padding: 12px;
  border-radius: 12px;
  border: 1px solid #ddd;
  margin-bottom: 15px;
}

.scan {
  border: 2px dashed #7950f2;
  padding: 12px;
  border-radius: 12px;
  color: #5f3dc4;
  margin-bottom: 20px;
}

.btn-main {
  background: linear-gradient(135deg, #5f3dc4, #7950f2);
  color: white;
  padding: 14px;
  border-radius: 15px;
  border: none;
  width: 100%;
  font-size: 16px;
  font-weight: bold;
}
.footer {
  margin-top: 20px;
  font-size: 12px;
  color: gray;
}
</style>
</head>

<body>

<div class="container">
  <h1>Selamat Datang 👋</h1>
  <div class="subtitle">GusdurPoint - Pusat Pembayaran Digital</div>

  <div class="tab">
    <button class="active">💰 Cek Komisi</button>
    <button>🔐 Login Admin</button>
  </div>

  <input type="text" placeholder="Masukkan Member ID Anda...">

  <div class="scan">📷 Buka Kamera — Scan QR</div>

  <button class="btn-main">🔎 Cek Komisi Saya</button>

  <div class="footer">
    © 2026 GusdurPoint
  </div>
</div>

</body>
</html>
