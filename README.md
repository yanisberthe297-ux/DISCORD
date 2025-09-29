# DISCORD
<!doctype html>
<html lang="fr">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Invitation Discord</title>
    <meta name="description" content="Rejoignez notre serveur Discord officiel !" />
    <style>
      :root{--bg:#36393f;--card:#2f3136;--accent:#7289da;--text:#ffffff}
      *{box-sizing:border-box}
      body{margin:0;min-height:100vh;display:grid;place-items:center;background:var(--bg);font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial}
      .card{background:var(--card);padding:36px;border-radius:18px;box-shadow:0 10px 30px rgba(0,0,0,0.5);max-width:600px;width:90%;color:var(--text);display:grid;gap:18px;align-items:center;text-align:center}
      .logo{width:72px;height:72px;border-radius:12px;background:var(--accent);display:grid;place-items:center;font-weight:700;color:white;font-size:28px;margin:auto} 
      h1{margin:0;font-size:22px}
      p{margin:0;opacity:0.9}
      .btn{padding:14px 24px;border-radius:12px;border:0;font-weight:600;cursor:pointer;background:var(--accent);color:white;font-size:16px;transition:0.2s}
      .btn:hover{background:#5b6eae}
      .note{font-size:12px;color:rgba(255,255,255,0.6)}
    </style>
  </head>
  <body>
    <main class="card">
      <div class="logo">DC</div>
      <h1>Rejoignez notre serveur Discord !</h1>
      <p class="note">Rencontrez notre communauté et discutez avec nos amis.</p>
      <button id="joinBtn" class="btn">Rejoindre le Discord</button>
      <p class="note">Le bouton ouvre un lien externe.</p>
    </main>

    <script>
      const targetUrl = 'https://www.roblox.com/share?code=c8536211006bdb4dafbaf052c662e6f1&type=Server';
      const btn = document.getElementById('joinBtn');
      btn.addEventListener('click', ()=>{
        btn.disabled = true;
        btn.textContent = 'Ouverture...';
        window.open(targetUrl, '_blank');
      });
    </script>
  </body>
</html>
