Game Design Document (GDD): Sesinho 80 Anos — Fragmentos da História
1. Visão Geral do Projeto
Conceito: Jogo comemorativo dos 80 anos do SESI. O jogador controla o "Sesinho" em uma aventura de plataforma/exploração para recuperar fragmentos históricos, coletar estrelas e reconstruir uma placa comemorativa. Público-alvo: Colaboradores do SESI. Objetivo Principal: Coletar 15 fragmentos históricos (5 por fase) e 240 estrelas (80 por fase) ao longo de 3 fases temáticas.

2. Identidade Visual e Áudio
Estilo de Arte: Inspirado em histórias em quadrinhos (HQs) clássicas.
Elementos Gráficos: Contornos marcados (cel-shading ou line art forte) e balões de fala para diálogos.
Efeitos Visuais (Onomatopeias): Devem aparecer no cenário durante ações específicas (pulos, colisões, coletas): POF!, BOING!, TCHIBUM!, ZUP!, POW!.
3. Mecânicas Principais (Core Mechanics)
Sistema de Pontuação (Estrelas):
Total de 240 estrelas no jogo (80 por fase).
Variável sugerida: stars_collected.
Sistema de Progressão (Fragmentos):
Total de 15 fragmentos (5 por fase). Representam pedaços da placa "SESI 80 ANOS".
Variável sugerida: fragments_collected.
Dicas de Proximidade:
Trigger: Quando o player se aproxima de um fragmento.
Ação: Exibir um balão de fala sobre o Sesinho com uma pergunta/curiosidade específica do fragmento.
Coleta de Fragmento:
Ação: Ao tocar no fragmento, pausar a ação brevemente.
UI: Exibir a mensagem "✨ FRAGMENTO RECUPERADO!" e mostrar o marco histórico em destaque na tela.
4. Inimigos e Obstáculos (Hazards)
Cada fase possui um inimigo temático. Ao encontrar o inimigo pela primeira vez, o jogo deve pausar e exibir uma janela estilo HQ apresentando o personagem.

Fase 1 - Engrenildo: Uma engrenagem travessa.
Apresentação: "⚙ Engrenildo está à solta! Não deixe essa engrenagem travessa atrapalhar sua missão."
Reação do Sesinho: "Uma engrenagem andando sozinha? Isso não parece nada normal!"
Fase 2 - Papelito: Um papel bagunceiro.
Apresentação: "📄 Papelito está causando confusão! Desvie das suas trapalhadas e continue a busca."
Reação do Sesinho: "Ei! Esse papel está bagunçando os registros históricos!"
Fase 3 - Disquetildo: Um disquete corrompido.
Apresentação: "💾 Disquetildo entrou no sistema! Recupere os fragmentos antes que ele os transforme em pixels! 🎮"
Reação do Sesinho: "Rápido! Antes que tudo vire código binário!"
5. Design de Fases (Level Design)
Fase 1: A Origem
Tema: Nascimento do SESI e primeiros investimentos.
Cenário: Fábricas antigas, engrenagens, chaminés, elementos industriais (estilo HQ).
Fragmentos a coletar:
Dica: “Você sabe quando começou essa grande história?” | Marco: 1946 — Criação do SESI por empresários brasileiros.
Dica: “O que será que ajudava os trabalhadores lá no começo?” | Marco: 1950 — Criação das Cozinhas Distritais.
Dica: “Será que encontramos algo relacionado à alimentação?” | Marco: 1954 — Expansão dos postos médicos.
Dica: “Onde os trabalhadores buscavam cuidados com a saúde?” | Marco: Saúde, alimentação e moradia para trabalhadores.
Dica: “Quais eram as principais necessidades das famílias naquela época?” | Marco: Nasce uma instituição dedicada ao bem-estar da indústria.
Encerramento da Fase: Balão do Sesinho: "Estamos descobrindo como tudo começou!"
Fase 2: Transformando Vidas
Tema: Educação, esporte, cultura e desenvolvimento humano.
Cenário: Escola SESI, biblioteca, quadras esportivas, teatro, espaços de convivência.
Fragmentos a coletar:
Dica: “Será que aprender a ler também fez parte dessa história?” | Marco: 1964 — Cursos de alfabetização para trabalhadores.
Dica: “Como o conhecimento ajudou a transformar vidas?” | Marco: 1972 — Centros esportivos para famílias industriárias.
Dica: “Além de estudar, qual outra atividade aproximava as pessoas?” | Marco: Expansão das atividades culturais.
Dica: “A diversão também pode fazer parte da educação?” | Marco: Atendimento às famílias dos trabalhadores.
Dica: “Quem mais foi beneficiado pelas ações do SESI?” | Marco: Educação, esporte e cultura transformando gerações.
Encerramento da Fase: Balão do Sesinho: "Cada fragmento mostra vidas sendo transformadas!"
Fase 3: Inovação e Futuro
Tema: Modernização, tecnologia e preparação para o futuro.
Cenário: Laboratórios, robótica, computadores, elementos tecnológicos (estilo HQ).
Fragmentos a coletar:
Dica: “Como a tecnologia ajudou a proteger os trabalhadores?” | Marco: 1985 — Programas de segurança nas fábricas.
Dica: “Quantas conquistas cabem em meio século de história?” | Marco: 1996 — SESI completa 50 anos.
Dica: “O que acontece quando educação e tecnologia se unem?” | Marco: 2008 — Expansão das escolas de Ensino Médio com foco em ciência e tecnologia.
Dica: “Robôs também fazem parte desta aventura?” | Marco: 2013 — Investimento em torneios de robótica.
Dica: “Qual será o segredo para continuar transformando o futuro?” | Marco: Hoje: líder em educação, saúde, bem-estar e segurança do trabalho.
Encerramento da Fase: Balão do Sesinho: "Falta pouco para completar os 80 anos de história!"
6. Interface de Usuário (UI) e Fluxo de Telas
Tela de Fim de Fase
Exibir painel de "Resultado da Fase".
Mostrar contadores: Estrelas coletadas: [X]/80 e Fragmentos recuperados: [X]/5.
Mensagem: "Você recuperou [X] de 5 fragmentos."
Exibir lista dos marcos históricos encontrados na fase.
Animação da placa comemorativa evoluindo/sendo montada.
Tela Final (Game Over / Vitória)
Título: 🏆 MISSÃO CONCLUÍDA
Texto: "Os 15 registros históricos foram recuperados."
Animação: A placa comemorativa é totalmente revelada com o texto "SESI 80 ANOS".
Score Final: Total de estrelas: [X]/240 | Total de fragmentos: 15/15.
Mensagem de Encerramento: "Há 80 anos, milhares de pessoas ajudam a transformar vidas por meio da educação, saúde, bem-estar e segurança. Hoje, essa história continua sendo escrita por pessoas como você."
Módulo de Compartilhamento (Social Share)
Funcionalidade: Gerar uma imagem exportável (para Feed ou Stories do Instagram/LinkedIn).
Composição da Imagem: Foto do colaborador (upload ou avatar) + Placa comemorativa SESI 80 ANOS + Identidade visual da campanha.
Texto Padrão para Postagem: "SESI 80 ANOS. Há 80 anos transformando vidas. Tenho orgulho de fazer parte dessa trajetória."
Você gostaria que eu detalhasse a lógica de programação de alguma mecânica específica, como o sistema de colisão dos fragmentos ou a geração da imagem final?