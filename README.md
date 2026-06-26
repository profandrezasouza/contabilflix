<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Contabilflix</title>
    <style>
        body { background-color: #141414; color: #ffffff; font-family: Arial, sans-serif; padding: 20px; }
        .header { border-bottom: 3px solid #e50914; padding-bottom: 10px; margin-bottom: 20px; }
        .logo { font-size: 28pt; font-weight: bold; color: #e50914; text-transform: uppercase; letter-spacing: -1px; }
        .banner { background-color: #222; padding: 15px; border-radius: 5px; margin-bottom: 20px; border-left: 5px solid #e50914; }
        .title { font-size: 16pt; font-weight: bold; color: #2ecc71; margin-top: 30px; }
        .title.comercial { color: #3498db; }
        .title.analise { color: #f1c40f; }
        .box { background-color: #181818; border: 1px solid #2d2d2d; padding: 15px; border-radius: 5px; margin-bottom: 15px; }
        .sinopse { color: #aaa; font-style: italic; margin-bottom: 15px; }
        
        /* Estilização do botão de clique */
        details summary { 
            cursor: pointer; 
            color: #e50914; 
            font-weight: bold; 
            outline: none;
            padding: 5px 0;
        }
        details summary:hover { text-decoration: underline; }
        
        /* Caixa do gabarito oculto */
        .gabarito { 
            background-color: #262626; 
            color: #fff; 
            padding: 15px; 
            border-left: 4px solid #e50914; 
            margin-top: 10px; 
            border-radius: 0 4px 4px 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">Contabilflix</div>
        <p>Temporada 2026.1 • Maratona de Elite</p>
    </div>
    
    <div class="banner">
        <strong>[Original] Ementa do Semestre:</strong> Prepare a sua mente analítica. Teste os seus conhecimentos com as questões interativas abaixo. Clique em cada episódio para abrir o gabarito escondido.
    </div>
    
    <div class="title">🟢 Temporada 1: Contabilidade Básica</div>
    <div class="box">
        <div><strong>E01: O Mistério do Balanço Desequilibrado</strong></div>
        <div class="sinopse">Uma empresa adquire uma máquina à vista por R$ 50.000,00. Qual o impacto no Ativo e no PL?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">Fato Permutativo. O Ativo permanece inalterado no total (sai do Caixa e entra no Imobilizado). O Patrimônio Líquido não se altera.</div>
        </details>
    </div>
    <div class="box">
        <div><strong>E02: A Origem dos Recursos</strong></div>
        <div class="sinopse">De onde vêm os recursos que financiam as aplicações do Ativo?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">Passivo Circulante/Não Circulante (Capitais de Terceiros) e Patrimônio Líquido (Capital Próprio).</div>
        </details>
    </div>

    <div class="title comercial">🔵 Temporada 2: Contabilidade Comercial</div>
    <div class="box">
        <div><strong>E03: O Imposto Recuperável</strong></div>
        <div class="sinopse">Compra de mercadorias por R$ 10.000,00 com ICMS incluso de 18%. Custo do estoque?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">O ICMS é recuperável. Custo do Estoque = R$ 10.000,00 - R$ 1.800,00 = R$ 8.200,00.</div>
        </details>
    </div>
    <div class="box">
        <div><strong>E04: O Confronto do CMV</strong></div>
        <div class="sinopse">Estoque Inicial = 2.000, Compras = 7.000, Estoque Final = 1.500. Qual o CMV?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">CMV = EI + C - EF -> CMV = 2.000 + 7.000 - 1.500 = R$ 7.500,00.</div>
        </details>
    </div>

    <div class="title analise">🔴 Temporada 3: Análise das Demonstrações</div>
    <div class="box">
        <div><strong>E05: A Liquidez Seca</strong></div>
        <div class="sinopse">Por que excluímos os estoques no cálculo da Liquidez Seca?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">Porque os estoques são os ativos menos líquidos do Ativo Circulante, dependendo de esforço de venda.</div>
        </details>
    </div>
    <div class="box">
        <div><strong>E06: O Grau de Endividamento</strong></div>
        <div class="sinopse">Capital de Terceiros = 200.000 e PL = 100.000. Qual a dependência de terceiros?</div>
        <details>
            <summary>🔴 Clique aqui para assistir à Resolução</summary>
            <div class="gabarito">PCT = (200.000 / 100.000) x 100 = 200%. A empresa usa o dobro de capital alheio em relação ao próprio.</div>
        </details>
    </div>
</body>
</html>
