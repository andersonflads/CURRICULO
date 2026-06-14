# CURRICULO
Dados profissionais e pessoais em HTML

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anderson de Freitas Leal - Currículo</title>
    <style>
        :root {
            --primary-color: #1e3a8a; /* Azul escuro corporativo/bancário */
            --secondary-color: #334155; /* Slate escuro para textos secundários */
            --accent-color: #3b82f6; /* Azul moderno */
            --text-color: #1e293b;
            --bg-light: #f8fafc;
            --line-color: #e2e8f0;
        }

        body {
            font-family: 'Segoe UI', Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-light);
            margin: 0;
            padding: 0;
        }

        .resume-container {
            max-width: 800px;
            margin: 3rem auto;
            background: #ffffff;
            padding: 3.5rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.05);
            border-radius: 8px;
        }

        /* Cabeçalho */
        header {
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 1.5rem;
            margin-bottom: 2rem;
        }

        header h1 {
            margin: 0 0 0.5rem 0;
            font-size: 2.4rem;
            color: var(--primary-color);
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        header p {
            margin: 0;
            color: var(--accent-color);
            font-size: 1.2rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .contact-info {
            margin-top: 1.2rem;
            font-size: 0.95rem;
            color: var(--secondary-color);
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .contact-info span {
            display: inline-flex;
            align-items: center;
        }

        .contact-info a {
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 500;
        }

        .contact-info a:hover {
            color: var(--accent-color);
            text-decoration: underline;
        }

        /* Seções */
        section {
            margin-bottom: 2.2rem;
        }

        section h2 {
            font-size: 1.2rem;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 1.2rem;
            border-bottom: 1px solid var(--line-color);
            padding-bottom: 0.4rem;
            font-weight: 700;
        }

        .summary-text {
            font-size: 1rem;
            color: #475569;
            text-align: justify;
        }

        /* Itens de Experiência/Educação */
        .resume-item {
            margin-bottom: 1.8rem;
        }

        .item-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 0.2rem;
        }

        .item-title {
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        .item-company {
            font-weight: 600;
            color: var(--secondary-color);
            font-size: 1rem;
        }

        .item-date {
            font-size: 0.9rem;
            color: #64748b;
            font-weight: 600;
            white-space: nowrap;
        }

        .resume-item ul {
            margin: 0.5rem 0 0 0;
            padding-left: 1.2rem;
            color: #475569;
        }

        .resume-item li {
            margin-bottom: 0.4rem;
        }

        /* Certificações e Tags */
        .badge-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem;
        }

        .badge-tag {
            background-color: #eff6ff;
            color: var(--primary-color);
            padding: 0.6rem 1rem;
            border-radius: 6px;
            font-size: 0.9rem;
            font-weight: 600;
            border: 1px solid #bfdbfe;
        }

        .badge-tag.cert {
            background-color: #f0fdf4;
            color: #166534;
            border-color: #bbf7d0;
        }

        /* Ajustes de Impressão / PDF */
        @media print {
            body { background-color: #fff; }
            .resume-container { 
                box-shadow: none; 
                padding: 0; 
                margin: 0;
            }
        }

        @media (max-width: 600px) {
            .resume-container { padding: 1.5rem; margin: 1rem; }
            .item-header { flex-direction: column; }
            .item-date { margin-top: 0.2rem; }
        }
    </style>
</head>
<body>

    <div class="resume-container">
        
        <!-- Cabeçalho -->
        <header>
            <h1>Anderson de Freitas Leal</h1>
            <p>Especialista em Negócios Bancários & Tecnologia (Dev/Sistemas)</p>
            
            <div class="contact-info">
                <span>📍 Brasília, DF</span> | 
                <span>📞 (61) 99938-1499</span> | 
                <span>✉️ <a href="mailto:andersonfleal77@gmail.com">andersonfleal77@gmail.com</a></span> | 
                <span>🔗 <a href="https://linkedin.com/in/anderson-freitas-754909409" target="_blank">linkedin.com/in/anderson-freitas-754909409</a></span>
            </div>
        </header>

        <!-- Resumo Profissional -->
        <section>
            <h2>Resumo Profissional</h2>
            <p class="summary-text">
                Profissional com sólida carreira de mais de 15 anos no mercado financeiro e bancário, atuando fortemente na prospecção de negócios, concessão de crédito, investimentos e atendimento estratégico ao cliente. Atualmente, unindo a sólida bagagem de negócios à transição tecnológica através do curso de Análise e Desenvolvimento de Sistemas, visando aplicar inteligência de dados, lógica de programação e automação na otimização de processos do setor financeiro.
            </p>
        </section>

        <!-- Experiência Profissional -->
        <section>
            <h2>Experiência Profissional</h2>
            
            <!-- Banco do Brasil -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Especialista em Atendimento e Negócios</span>
                    <span class="item-date">Out 2007 — Presente</span>
                </div>
                <div class="item-company">Banco do Brasil S.A. — Brasília, DF</div>
                <ul>
                    <li>Gestão de carteira de clientes, comercialização de produtos financeiros e soluções de crédito e investmento.</li>
                    <li><strong>Cargos anteriores ocupados na instituição:</strong> Supervisor de Atendimento, Assistente de Negócios, Assistente Operacional, Caixa Executivo e Escriturário.</li>
                    <li>Liderança de equipes de atendimento e garantia do cumprimento de metas operacionais e de conformidade (compliance).</li>
                </ul>
            </div>

            <!-- Cooperforte -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Analista de Negócios</span>
                    <span class="item-date">Jul 2005 — Jun 2006</span>
                </div>
                <div class="item-company">Cooperforte (Cooperativa de Crédito e Investimento LTDA) — Brasília, DF</div>
                <ul>
                    <li>Atuação estratégica na prospecção ativa de novos clientes para o quadro de cooperados.</li>
                    <li>Análise de perfil financeiro para concessão de linhas de crédito e estruturação de ofertas de investimentos.</li>
                </ul>
            </div>

            <!-- CNPq -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Estagiário</span>
                    <span class="item-date">Jan 2004 — Mai 2006</span>
                </div>
                <div class="item-company">CNPq (Conselho Nacional de Desenvolvimento Científico e Tecnológico) — Brasília, DF</div>
                <ul>
                    <li>Suporte e atendimento direto a pesquisadores e alunos de graduação/pós-graduação.</li>
                    <li>Análise e validação documental em sistemas governamentais para cadastros de projetos e concessão de bolsas de fomento à pesquisa.</li>
                </ul>
            </div>
        </section>

        <!-- Formação Acadêmica -->
        <section>
            <h2>Formação Acadêmica</h2>
            
            <!-- Graduação Atual -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Tecnólogo em Análise e Desenvolvimento de Sistemas</span>
                    <span class="item-date">Cursando (1º Semestre)</span>
                </div>
                <div class="item-company">CEUB — Centro Universitário de Brasília (Taguatinga Sul)</div>
            </div>

            <!-- Pós-Graduação -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Pós-Graduação em Gestão Econômica e Financeira</span>
                    <span class="item-date">Out 2016 — Out 2017</span>
                </div>
                <div class="item-company">FETAC — Faculdade de Educação, Tecnologia e Administração de Caarapó</div>
            </div>

            <!-- Bacharelado -->
            <div class="resume-item">
                <div class="item-header">
                    <span class="item-title">Bacharel em Administração</span>
                    <span class="item-date">Jan 2000 — Dez 2006</span>
                </div>
                <div class="item-company">UCB — Universidade Católica de Brasília (Taguatinga Sul)</div>
            </div>
        </section>

        <!-- Certificações e Competências -->
        <section>
            <h2>Certificações & Competências</h2>
            <div class="badge-grid">
                <div class="badge-tag cert">ANBIMA CPA-10</div>
                <div class="badge-tag">Análise Financeira</div>
                <div class="badge-tag">Concessão de Crédito</div>
                <div class="badge-tag">Gestão de Investimentos</div>
                <div class="badge-tag">Lógica de Programação</div>
                <div class="badge-tag">Análise de Sistemas</div>
                <div class="badge-tag">Gestão de Equipes</div>
            </div>
        </section>

    </div>

</body>
</html>
