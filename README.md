<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Camily Guilherme</title>
    <style>
        :root {
            --cor-primaria: #2c3e50;
            --cor-secundaria: #3498db;
            --cor-destaque: #e74c3c;
            --cor-fundo: #ecf0f1;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 2rem;
            padding: 2rem;
            background: var(--cor-fundo);
            color: var(--cor-primaria);
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 2rem;
        }

        .header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--cor-secundaria);
            margin-bottom: 1rem;
        }

        .nome {
            font-size: 2.5rem;
            color: var(--cor-primaria);
            margin: 0.5rem 0;
        }

        .cargo {
            font-size: 1.2rem;
            color: var(--cor-secundaria);
            margin-bottom: 1rem;
        }

        .secao {
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid var(--cor-secundaria);
        }

        .secao h2 {
            color: var(--cor-destaque);
            margin-bottom: 1rem;
        }

        .info-item {
            display: flex;
            align-items: center;
            margin: 0.8rem 0;
        }

        .info-item svg {
            margin-right: 0.5rem;
            color: var(--cor-secundaria);
        }

        .progresso {
            background: #e0e0e0;
            border-radius: 10px;
            height: 8px;
            margin: 1rem 0;
        }

        .progresso-fill {
            background: var(--cor-destaque);
            width: 85%;
            height: 100%;
            border-radius: 10px;
        }

        .habilidades {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 1rem;
        }

        .habilidade-item {
            padding: 1rem;
            text-align: center;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .footer {
            text-align: center;
            margin-top: 2rem;
        }

        .footer a {
            color: var(--cor-secundaria);
            text-decoration: none;
            margin: 0 0.5rem;
        }

        @media (max-width: 600px) {
            .nome {
                font-size: 2rem;
            }
            
            .header img {
                width: 120px;
                height: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://via.placeholder.com/150" alt="Foto de Perfil">
            <div class="nome">Camily Guilherme</div>
            <div class="cargo">Desenvolvedora Front-End</div>
        </div>

        <div class="secao">
            <h2>Sobre</h2>
            <div class="info-item">
                📅 Idade: 21 anos
            </div>
            <div class="info-item">
                🎓 Formação: Análise e Desenvolvimento de Sistemas (3º Período) - FAMINAS/MG
            </div>
        </div>

        <div class="secao">
            <h2>Habilidades</h2>
            <div class="progresso">
                <div class="progresso-fill"></div>
            </div>
            <div class="habilidades">
                <div class="habilidade-item">JavaScript</div>
                <div class="habilidade-item">HTML5</div>
                <div class="habilidade-item">CSS3</div>
                <div class="habilidade-item">React</div>
                <div class="habilidade-item">Power BI</div>
                <div class="habilidade-item">Banco de Dados</div>
            </div>
        </div>

        <div class="footer">
            <a href="https://github.com/seu-usuario" target="_blank">GitHub</a>
            ·
            <a href="#">LinkedIn</a>
        </div>
    </div>
</body>
</html>
