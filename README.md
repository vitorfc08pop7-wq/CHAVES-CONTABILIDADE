# CHAVES-CONTABILIDADE
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Chaves Contabilidade - Soluções Contábeis</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    background: #f4f4f4;
    color: #222;
  }
  header {
    background: #000000;
    color: white;
    padding: 25px 20px;
    text-align: center;
  }
  header h1 {
    margin: 0;
    color: #00BFFF; /* Azul */
    font-size: 2.8rem;
  }
  header p {
    margin-top: 8px;
    font-size: 1.2rem;
  }

  section.servicos {
    max-width: 1200px;
    margin: 30px auto;
    padding: 0 20px;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  .servico {
    flex: 1 1 280px;
    padding: 20px;
    border-radius: 10px;
    color: white;
    box-shadow: 0 0 12px rgb(0 0 0 / 0.15);
  }
  .vermelho { background-color: #ff0000; }
  .preto { background-color: #000000; color: #00ff00; } /* preto com texto verde */
  .azul { background-color: #0033cc; }
  .verde { background-color: #008000; }

  .servico h3 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 1.5rem;
  }
  .servico p {
    font-size: 1rem;
    line-height: 1.4;
  }

  section.resultados {
    max-width: 800px;
    margin: 40px auto 60px auto;
    padding: 0 20px;
  }

  section.depoimentos {
    max-width: 900px;
    margin: 0 auto 60px auto;
    padding: 0 20px;
  }
  blockquote {
    border-left: 6px solid;
    padding-left: 15px;
    margin: 20px 0;
    font-style: italic;
    color: #333;
    background: #fff;
    box-shadow: 0 0 8px rgb(0 0 0 / 0.1);
    border-radius: 5px;
  }
  blockquote.vermelho { border-color: #ff0000; }
  blockquote.verde { border-color: #008000; }

  section.contato {
    background: #0033cc;
    color: white;
    max-width: 500px;
    margin: 0 auto 60px auto;
    padding: 25px 30px;
    border-radius: 12px;
    text-align: center;
  }
  section.contato p {
    font-size: 1.2rem;
    margin: 12px 0;
  }
  section.contato a {
    color: #00ff00;
    text-decoration: none;
    font-weight: bold;
  }
  button.orcamento {
    background-color: #ff0000;
    border: none;
    color: white;
    font-size: 1.2rem;
    padding: 14px 30px;
    border-radius: 7px;
    cursor: pointer;
    margin-top: 20px;
    transition: background-color 0.3s ease;
  }
  button.orcamento:hover {
    background-color: #cc0000;
  }

  footer {
    text-align: center;
    padding: 20px;
    background: #222;
    color: #ddd;
    font-size: 0.9rem;
  }

  @media(max-width: 600px){
    section.servicos {
      flex-direction: column;
      gap: 15px;
    }
    .servico {
      flex: 1 1 100%;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Chaves Contabilidade</h1>
  <p>Seu parceiro em soluções contábeis para fazer seu negócio crescer!</p>
</header>

<section class="servicos" aria-label="Serviços oferecidos pela Chaves Contabilidade">

  <div class="servico vermelho" tabindex="0">
    <h3>Contabilidade Empresarial</h3>
    <p>Controle total da sua contabilidade, com balanços, demonstrações e obrigações acessórias.</p>
  </div>

  <div class="servico preto" tabindex="0">
    <h3>Departamento Pessoal</h3>
    <p>Folha de pagamento, admissões, demissões e gestão completa de colaboradores.</p>
  </div>

  <div class="servico azul" tabindex="0">
    <h3>Consultoria Fiscal</h3>
    <p>Planejamento tributário e orientação para reduzir impostos legalmente.</p>
  </div>

  <div class="servico verde" tabindex="0">
    <h3>Gestão Financeira</h3>
    <p>Controle de fluxo de caixa, análise de custos e tomada de decisão eficiente.</p>
  </div>

  <div class="servico vermelho" tabindex="0">
    <h3>Auditoria e Perícia Contábil</h3>
    <p>Avaliação técnica e imparcial para assegurar a saúde financeira da empresa.</p>
  </div>

  <div class="servico preto" tabindex="0" style="color: #00ffff;">
    <h3>Compras e Licitações</h3>
    <p>Assistência especializada para processos públicos e privados, com total conformidade legal.</p>
  </div>

</section>

<section class="resultados" aria-label="Gráfico dos serviços mais solicitados">
  <h2 style="text-align:center; color:#0033cc; margin-bottom: 20px;">Serviços mais solicitados</h2>
  <canvas id="serviceChart" width="700" height="400"></canvas>
</section>

<section class="depoimentos" aria-label="Depoimentos de clientes">
  <blockquote class="vermelho" tabindex="0">
    "A Chaves Contabilidade transformou a gestão financeira da nossa empresa. Atendimento ágil e transparente!" <br> — João Silva, Empresário.
  </blockquote>

  <blockquote class="verde" tabindex="0">
    "Profissionalismo e confiança que fazem toda a diferença. Recomendo sem dúvidas!" <br> — Maria Oliveira, Microempreendedora.
  </blockquote>
</section>

<section class="contato" aria-label="Informações de contato">
  <p><strong>WhatsApp:</strong> <a href="https://wa.me/5594999556945" target="_blank" rel="noopener noreferrer">(94) 99995-56945</a></p>
  <p><strong>E-mail:</strong> <a href="mailto:chaves.contabilidade94@gmail.com">chaves.contabilidade94@gmail.com</a></p>
  <button class="orcamento" onclick="window.location.href='https://wa.me/5594999556945?text=Olá,%20gostaria%20de%20solicitar%20um%20orçamento%20para%20serviços%20contábeis.'">Solicitar Orçamento</button>
</section>

<footer>
  &copy; 2025 Chaves Contabilidade - Todos os direitos reservados.
</footer>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  const ctx = document.getElementById('serviceChart').getContext('2d');
  const serviceChart = new Chart(ctx, {
      type: 'bar',
      data: {
          labels: ['Contabilidade', 'Departamento Pessoal', 'Consultoria Fiscal', 'Gestão Financeira', 'Auditoria', 'Licitações'],
          datasets: [{
              label: 'Solicitações (%)',
              data: [35, 25, 15, 10, 8, 7],
              backgroundColor: [
                  'rgba(255, 0, 0, 0.7)',
                  'rgba(0, 255, 0, 0.7)',
                  'rgba(0, 51, 204, 0.7)',
                  'rgba(0, 128, 0, 0.7)',
                  'rgba(255, 0, 0, 0.7)',
                  'rgba(0, 255, 255, 0.7)'
              ],
              borderColor: [
                  'rgba(255, 0, 0, 1)',
                  'rgba(0, 255, 0, 1)',
                  'rgba(0, 51, 204, 1)',
                  'rgba(0, 128, 0, 1)',
                  'rgba(255, 0, 0, 1)',
                  'rgba(0, 255, 255, 1)'
              ],
              borderWidth: 1
          }]
      },
      options: {
          scales: {
              y: {
                  beginAtZero: true,
                  max: 40
              }
          },
          plugins: {
            legend: {
              labels: {
                color: '#222',
                font: {
                  size: 16
                }
              }
            }
          }
      }
  });
</script>

</body>
</html>
