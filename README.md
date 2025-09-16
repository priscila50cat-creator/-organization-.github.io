# -organization-.github.io
import qrcode
qr = qrcode.QRCode(error_correction=qrcode.constants.ERROR_CORRECT_H)
qr.add_data("https://seu-usuario.github.io/seu-repo/")
qr.make(fit=True)
img = qr.make_image(format="SVG")
with open("qr_setembro_amarelo.svg","wb") as f:
    f.write(img.getvalue())
setembro amarelo enfermagem á favor da vida´´um gesto de cuidado pode salvar uma vida´´
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Setembro Amarelo — Valorize a Vida</title>
  <style>
    :root{--bg:#fffbe6;--accent:#f5c542;--text:#222;}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial; margin:0; color:var(--text); background:var(--bg); line-height:1.5;}
    header{background:linear-gradient(90deg,rgba(245,197,66,0.12),transparent); padding:28px 16px; text-align:center;}
    .container{max-width:820px;margin:18px auto;padding:0 16px;}
    h1{margin:0;font-size:1.6rem;}
    p.lead{margin:8px 0 18px;color:#333;}
    .card{background:#fff;padding:14px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.06); margin-bottom:12px;}
    .tips li{margin:8px 0;}
    .actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:8px;}
    .btn{background:var(--accent);padding:10px 12px;border-radius:10px;text-decoration:none;color:#111;font-weight:600;}
    footer{font-size:0.85rem;color:#444;text-align:center;margin:18px 0 36px;}
    .danger{color:#a00;font-weight:700;}
    @media(min-width:720px){h1{font-size:2rem}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Setembro Amarelo — Valorize a Vida</h1>
      <p class="lead">Pequenas práticas de autocuidado e formas de pedir ajuda. Se estiver em risco, busque ajuda imediata.</p>
    </div>
  </header>

  <main class="container">
    <section class="card" aria-labelledby="o-que">
      <h2 id="o-que">O que é ?</h2>
      <p>Setembro Amarelo é um movimento de conscientização sobre prevenção ao suicídio. Se precisar conversar, não está sozinho(a).</p>
      <p>Saiba mais sobre a campanha: <a href="https://setembroamarelo.org.br" target="_blank" rel="noopener">SetembroAmarelo.org.br</a>. 2</p>
    </section>

    <section class="card" aria-labelledby="dicas">
      <h2 id="dicas">Dicas práticas de autoajuda</h2>
      <ul class="tips">
        <li>Fale com alguém de confiança — um amigo, familiar ou colega.</li>
        <li>Estabeleça pequenas rotinas diárias (sono, alimentação, caminhada).</li>
        <li>Pratique respiração 4-4-4 (inspira 4s, segura 4s, expira 4s) quando estiver ansioso(a).</li>
        <li>Se possível, evite álcool e substâncias que aumentem a impulsividade.</li>
        <li>Procure ajuda profissional: psicólogo, psiquiatra ou serviço de saúde local.</li>
      </ul>
    </section>

    <section class="card" aria-labelledby="contatos">
      <h2 id="contatos">Contatos de ajuda imediata</h2>
      <p>Se você está no Brasil, o <strong>CVV</strong> oferece apoio emocional 24h: <a href="https://cvv.org.br" target="_blank" rel="noopener">cvv.org.br</a> — telefone <a href="tel:188">188</a>. 3</p>
      <p>Informações oficiais sobre prevenção no site do Ministério da Saúde: <a href="https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/s/suicidio-prevencao" target="_blank" rel="noopener">Saúde.gov.br</a>. 4</p>

      <div class="actions">
        <a class="btn" href="tel:188">Ligar para 188</a>
        <a class="btn" href="https://cvv.org.br" target="_blank" rel="noopener">Chat do CVV</a>
      </div>
    </section>

    <section class="card" aria-labelledby="quando-procurar">
      <h2 id="quando-procurar">Quando procurar ajuda profissional</h2>
      <p class="danger">Se você tem pensamentos de ferir a si mesmo(a) ou acha que pode agir, procure ajuda imediatamente ou ligue 188.</p>
      <p>Procure também quando sentir falta de esperança, isolamento persistente, alterações de sono/apetite ou pensamentos repetitivos sobre morte.</p>
    </section>
  </main>

  <footer>
    <div class="container">Se for para compartilhar este conteúdo: inclua sempre avisos e contatos locais de emergência. © Setembro Amarelo — Valorize a Vida.</div>
  </footer>
</body>
</html>
