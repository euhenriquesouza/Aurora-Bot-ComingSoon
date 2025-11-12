
<!doctype html>

<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Aurora Bot — Em breve</title>
  <meta name="description" content="Aurora Bot — a nova era da automação no Discord. Em breve pela Simple Solutions." />
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    :root{
      --bg1:#0f1724; --bg2:#071029;
      --accent1:#8be9fd; --accent2:#b28cff; --glass:rgba(255,255,255,0.06);
      --card-shadow: 0 10px 30px rgba(2,6,23,0.6);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;padding:0;min-height:100%;background:radial-gradient(1200px 600px at 10% 10%, rgba(178,140,255,0.08), transparent 10%), linear-gradient(135deg,var(--bg1),var(--bg2));
      color: #e6eef8; -webkit-font-smoothing:antialiased;
    }.aurora{position:fixed;inset:0;pointer-events:none;mix-blend-mode:screen;opacity:0.55;background:linear-gradient(120deg, rgba(139,233,253,0.06), rgba(178,140,255,0.06));filter:blur(60px);animation: slowDrift 18s ease-in-out infinite alternate;}
@keyframes slowDrift{from{transform:translateY(0) rotate(0deg)}to{transform:translateY(-30px) rotate(6deg)}}

.stars{position:fixed;inset:0;pointer-events:none;background-image:radial-gradient(circle at 20% 30%, rgba(255,255,255,0.06) 0 1px, transparent 1px), radial-gradient(circle at 70% 60%, rgba(255,255,255,0.04) 0 1px, transparent 1px);background-size: 400px 400px, 600px 600px;opacity:0.45}

.container{max-width:1100px;margin:40px auto;padding:36px}
header{display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{display:flex;align-items:center;gap:14px}
.logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent1),var(--accent2));box-shadow:0 6px 24px rgba(139,233,253,0.08);display:flex;align-items:center;justify-content:center;font-weight:700;color:#041224}
.brand h1{margin:0;font-size:20px;letter-spacing:0.4px}
.subtitle{font-size:12px;color:rgba(230,238,248,0.65)}

main{display:grid;grid-template-columns:1fr 420px;gap:28px;margin-top:28px}

.hero{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:28px;border-radius:16px;box-shadow:var(--card-shadow);backdrop-filter: blur(6px);border:1px solid rgba(255,255,255,0.04)}
.hero h2{margin:0 0 12px 0;font-size:26px}
.hero p{margin:0 0 18px 0;color:rgba(230,238,248,0.85);line-height:1.5}

.typing{display:inline-block;color:var(--accent1);font-weight:600}

.features{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:18px}
.feat{background:var(--glass);padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);font-size:14px;display:flex;align-items:center;gap:8px}

.sideCard{padding:20px;border-radius:14px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03);box-shadow:0 8px 28px rgba(4,6,12,0.6)}
.status{display:flex;align-items:center;gap:10px}
.dot{width:12px;height:12px;border-radius:50%;background:linear-gradient(180deg,#45f3ff,#7b6bff);box-shadow:0 6px 18px rgba(123,107,255,0.12)}
.progress{margin-top:16px;background:rgba(255,255,255,0.03);height:12px;border-radius:999px;overflow:hidden}
.progress > i{display:block;height:100%;width:58%;background:linear-gradient(90deg,var(--accent1),var(--accent2));transition:width .9s cubic-bezier(.2,.9,.3,1)}

.badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:18px}
.badge{padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);font-size:12px;border:1px solid rgba(255,255,255,0.02)}

.cta{display:flex;gap:12px;margin-top:20px}
.btn{padding:11px 16px;border-radius:12px;border:0;cursor:pointer;font-weight:700;background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#041224}
.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:rgba(230,238,248,0.95)}

footer{margin-top:40px;color:rgba(230,238,248,0.55);font-size:13px;display:flex;justify-content:space-between;align-items:center}

@media (max-width:980px){main{grid-template-columns:1fr} .container{padding:18px} .logo{width:48px;height:48px}}

.fade-up{opacity:0;transform:translateY(10px);animation:fadeUp .8s forwards}
.delay-1{animation-delay:0.08s}
.delay-2{animation-delay:0.18s}
.delay-3{animation-delay:0.28s}
.delay-4{animation-delay:0.38s}
@keyframes fadeUp{to{opacity:1;transform:none}}

.float{animation: floaty 6s ease-in-out infinite}
@keyframes floaty{0%{transform:translateY(0)}50%{transform:translateY(-6px)}100%{transform:translateY(0)}}

pre{background:rgba(2,6,23,0.65);padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.02);overflow:auto}

  </style>
</head>
<body>
  <div class="aurora"></div>
  <div class="stars"></div>  <div class="container">
    <header class="fade-up delay-1">
      <div class="brand">
        <div class="logo float">A</div>
        <div>
          <h1>Aurora Bot</h1>
          <div class="subtitle">Em breve — Simple Solutions</div>
        </div>
      </div>
      <nav class="fade-up delay-2" aria-hidden>
        <span class="badge">Status: Em desenvolvimento</span>
        <span class="badge">Tecnologia: discord.js • Node.js</span>
      </nav>
    </header><main>
  <section class="hero fade-up delay-2">
    <h2><i class="fas fa-sun"></i> Uma nova luz para o seu servidor Discord</h2>
    <p>Aurora Bot é um sistema de automação pensado para suporte, moderação e integração com produtos da <strong>Simple Solutions</strong>. Rápido, confiável e com uma interface moderna — projetado para reduzir trabalho manual e aumentar a eficiência.</p>

    <p><span class="typing" id="typing"></span></p>

    <div class="features">
      <div class="feat"><i class="fas fa-ticket-alt"></i> Tickets totalmente automatizados</div>
      <div class="feat"><i class="fas fa-cogs"></i> Painel de configurações (em breve)</div>
      <div class="feat"><i class="fas fa-lock"></i> Segurança e permissões avançadas</div>
      <div class="feat"><i class="fas fa-chart-line"></i> Logs e estatísticas inteligentes</div>
    </div>

    <div class="cta">
      <button class="btn"><i class="fas fa-rocket"></i> Quero testar (em breve)</button>
      <button class="btn ghost"><i class="fas fa-road"></i> Ver roadmap</button>
    </div>

    <div style="margin-top:18px">
      <pre><strong>Instalação (prévia)</strong>

npm install aurora-bot </pre> </div> </section>

<aside class="sideCard fade-up delay-3">
    <div style="display:flex;justify-content:space-between;align-items:center">
      <div>
        <div class="status"><span class="dot"></span><strong>Progresso</strong></div>
        <div style="margin-top:6px;color:rgba(230,238,248,0.75)">Desenvolvimento ativo — versão alfa interna</div>
      </div>
      <div style="text-align:right">
        <div style="font-weight:800;font-size:20px">v0.1.0</div>
        <div style="font-size:12px;color:rgba(230,238,248,0.6)">alpha</div>
      </div>
    </div>

    <div class="progress"><i style="width:58%"></i></div>

    <div class="badges">
      <div class="badge"><i class="fas fa-tools"></i> Em desenvolvimento</div>
      <div class="badge"><i class="fab fa-discord"></i> discord.js v14+</div>
      <div class="badge"><i class="fab fa-node"></i> Node 18+</div>
      <div class="badge"><i class="fas fa-code"></i> Simple Solutions</div>
    </div>

    <div style="margin-top:14px;font-size:13px;color:rgba(230,238,248,0.8)">Assine a lista de espera e seja notificado quando abrirmos testes!</div>
  </aside>
</main>

<footer class="fade-up delay-4">
  <div>© Simple Solutions — Aurora Bot</div>
  <div>Feito com <i class="fas fa-heart"></i> — Em breve no GitHub</div>
</footer>

  </div>  <script>
    const phrases = ['Tickets automáticos.', 'Painel intuitivo.', 'Segurança reforçada.', 'Integrações inteligentes.'];
    let i=0, j=0, cur='';
    const el = document.getElementById('typing');
    function tick(){
      const phrase = phrases[i];
      cur = phrase.slice(0,++j);
      el.textContent = cur;
      if(j===phrase.length){
        setTimeout(()=>{ j=0; i=(i+1)%phrases.length; setTimeout(tick,200); },1000);
      } else setTimeout(tick,80);
    }
    tick();
  </script></body>
</html>
