# Perfil-Empreendedor
Descobrindo o meu Perfil Empreendedor 
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Questionário de Perfil Empreendedor — SENAC</title>
  <style>
    :root{--bg:#f5f7fb;--card:#ffffff;--accent:#0066a1;--muted:#6b7280}
    body{font-family:Arial, Helvetica, sans-serif;margin:0;background:var(--bg);color:#111}
    .container{max-width:900px;margin:28px auto;padding:20px}
    header{display:flex;align-items:center;gap:16px;flex-wrap:wrap}
    .logo img{max-width:140px;height:auto}
    h1{margin:0;font-size:1.6rem;color:var(--accent)}
    p.lead{color:var(--muted);margin:6px 0 18px}
    .card{background:var(--card);padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    .q{margin-bottom:16px}
    label.option{display:block;background:#f7fafc;border:1px solid #e6eef6;padding:10px;border-radius:8px;cursor:pointer;margin:6px 0}
    input[type="radio"], input[type="text"], textarea{margin-right:8px}
    input[type="text"], textarea, select{width:100%;padding:8px;border:1px solid #ccc;border-radius:6px;margin-top:4px}
    textarea{resize:vertical;min-height:60px}
    .actions{display:flex;gap:10px;align-items:center;margin-top:14px;flex-wrap:wrap}
    button{background:var(--accent);color:#fff;padding:10px 14px;border:0;border-radius:8px;cursor:pointer}
    button.secondary{background:#e6eef6;color:var(--accent)}
    .result{margin-top:18px;padding:14px;border-radius:8px;background:#f1f8ff;border:1px solid #dbeffb}
    .profile-title{font-weight:700;margin:0}
    .profile-desc{margin:6px 0 0;color:#333}
    small.note{display:block;margin-top:8px;color:var(--muted)}
    footer{margin-top:18px;font-size:0.9rem;color:var(--muted);text-align:center}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <!-- Logo SENAC -->
        <img src="senac_logo.png" alt="Logo SENAC" />
      </div>
      <div>
        <h1>Questionário de Perfil Empreendedor</h1>
        <p class="lead">Responda às perguntas. Ao final, você receberá seu perfil predominante: Explorador, Construtor, Sonhador ou Pragmático.</p>
      </div>
    </header>

    <form id="quiz" class="card" onsubmit="return false;">
      <fieldset>
        <legend><strong>1. Identificação (opcional)</strong></legend>
        <div class="q">
          <label for="nome">Nome:</label>
          <input type="text" id="nome" name="nome" placeholder="Digite seu nome (opcional)">
        </div>
        <div class="q">
          <label for="idade">Faixa etária:</label>
          <select id="idade" name="idade">
            <option value="">Selecione (opcional)</option>
            <option>Até 18 anos</option>
            <option>19 a 29 anos</option>
            <option>30 a 45 anos</option>
            <option>46 anos ou mais</option>
          </select>
        </div>
      </fieldset>

      <fieldset>
        <legend><strong>2. Perguntas situacionais</strong></legend>

        <div class="q">
          <p><strong>1.</strong> Imagine que recebeu uma proposta para trabalhar em uma área totalmente diferente da sua. O que faria?</p>
          <label class="option"><input type="radio" name="p1" value="explorador">Aceitaria, para experimentar e aprender algo novo.</label>
          <label class="option"><input type="radio" name="p1" value="construtor">Pensaria bastante, avaliando se isso combina com meu plano de longo prazo.</label>
          <label class="option"><input type="radio" name="p1" value="sonhador">Aceitaria se essa nova área estivesse alinhada a um propósito maior.</label>
          <label class="option"><input type="radio" name="p1" value="pragmatico">Analisaria os benefícios imediatos (salário, segurança) antes de decidir.</label>
        </div>

        <div class="q">
          <p><strong>2.</strong> Quando pensa no futuro, o que mais pesa na sua escolha profissional?</p>
          <label class="option"><input type="radio" name="p2" value="explorador">Ter experiências variadas e conhecer muitas áreas.</label>
          <label class="option"><input type="radio" name="p2" value="construtor">Crescer de forma consistente em uma carreira definida.</label>
          <label class="option"><input type="radio" name="p2" value="sonhador">Fazer algo que transforme vidas ou o mundo ao meu redor.</label>
          <label class="option"><input type="radio" name="p2" value="pragmatico">Garantir sustento, estabilidade e qualidade de vida.</label>
        </div>

        <div class="q">
          <p><strong>3.</strong> Diante de um desafio inesperado no trabalho ou estudo, como reage?</p>
          <label class="option"><input type="radio" name="p3" value="explorador">Vejo como uma chance de aprender algo novo.</label>
          <label class="option"><input type="radio" name="p3" value="construtor">Procuro aplicar o que já sei e seguir o plano.</label>
          <label class="option"><input type="radio" name="p3" value="sonhador">Me pergunto como esse desafio pode ter um impacto positivo maior.</label>
          <label class="option"><input type="radio" name="p3" value="pragmatico">Tento resolver da forma mais prática e rápida possível.</label>
        </div>

        <div class="q">
          <p><strong>4.</strong> Se pudesse descrever sua jornada em uma metáfora, qual escolheria?</p>
          <label class="option"><input type="radio" name="p4" value="explorador">Uma viagem cheia de paradas diferentes e surpresas.</label>
          <label class="option"><input type="radio" name="p4" value="construtor">Uma escada em que cada degrau é uma conquista.</label>
          <label class="option"><input type="radio" name="p4" value="sonhador">Uma missão em busca de um ideal ou sonho.</label>
          <label class="option"><input type="radio" name="p4" value="pragmatico">Uma estrada segura que me leva onde preciso chegar.</label>
        </div>
      </fieldset>

      <fieldset>
        <legend><strong>3. Perguntas reflexivas (abertas)</strong></legend>
        <div class="q">
          <label for="p5">5. Qual foi uma experiência de vida ou trabalho que marcou você?</label>
          <textarea id="p5" name="p5"></textarea>
        </div>
        <div class="q">
          <label for="p6">6. Que sonho ou objetivo você gostaria de realizar daqui para frente?</label>
          <textarea id="p6" name="p6"></textarea>
        </div>
        <div class="q">
          <label for="p7">7. Se pudesse resumir sua vocação em uma palavra, qual seria?</label>
          <input type="text" id="p7" name="p7">
        </div>
      </fieldset>

      <div class="actions">
        <button id="calcular">Calcular Perfil</button>
        <button type="button" class="secondary" id="limpar">Limpar</button>
 </div>

      <div id="resultado" class="result" style="display:none" aria-live="polite"></div>
    </form>

    <footer>
      © 2025 — Questionário de Perfil Empreendedor | SENAC
    </footer>
  </div>

  <script>
    document.getElementById("calcular").addEventListener("click", function(){
      const respostas = ["p1","p2","p3","p4"];
      const contagem = {explorador:0, construtor:0, sonhador:0, pragmatico:0};

      for(let r of respostas){
        let marcado = document.querySelector(`input[name="${r}"]:checked`);
        if(marcado){
          contagem[marcado.value]++;
        }
      }

      let perfil = Object.keys(contagem).reduce((a,b)=>contagem[a] > contagem[b] ? a : b);

      const descricoes = {
        explorador: "Você é curioso(a), gosta de experimentar novidades e valoriza a diversidade de experiências.",
        construtor: "Você prefere estabilidade, planejamento e crescimento consistente, degrau por degrau.",
        sonhador: "Você busca propósito, significado e deseja causar impacto positivo na vida das pessoas.",
        pragmatico: "Você é objetivo(a), valoriza soluções rápidas e práticas, focando em segurança e resultados imediatos."
      };

      const nome = document.getElementById("nome").value;
      const idade = document.getElementById("idade").value;

      let intro = "";
      if(nome || idade){
        intro = `<p><em>${nome ? nome : "Participante"}${idade ? ", " + idade : ""}</em></p>`;
      }

      document.getElementById("resultado").style.display = "block";
      document.getElementById("resultado").innerHTML = `
        ${intro}
        <p class="profile-title">Perfil Identificado: <strong>${perfil.toUpperCase()}</strong></p>
        <p class="profile-desc">${descricoes[perfil]}</p>
      `;
    });

    document.getElementById("limpar").addEventListener("click", function(){
      document.getElementById("quiz").reset();
      document.getElementById("resultado").style.display = "none";
    });
  </script>
</body>
</html>
