<h1 align="center">Luis Gustavo Cerqueira</h1>

<p align="center">
  <em>Engenharia de software · Modelagem de dados · Finanças quantitativas & Risco</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/luis-gustavo-cerqueira-b1482829a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:luisgustavo292005@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---

Estudante de **Sistemas de Informação na USP**, resolvo problemas complexos através de código, desde a modelagem de bancos de dados relacionais e sistemas concorrentes até o desenvolvimento de pipelines de dados, grafos e modelos de Machine Learning. Interesse especial na interseção entre engenharia de software, inteligência artificial e segurança aplicada a risco e mercado financeiro.

## 🏆 Projetos e Desafios em Destaque

### ⚡ Hackathon QI Tech 2026: Risk Solutions (Grupo Destaque)
Motor de decisão antifraude transacional as a Service para Pix, projetado para resposta em tempo real (< 500 ms), com inteligência de redes/grafos e fricção cirúrgica com falso-positivo mínimo.

<a href="https://github.com/Cerqueira11/hacka_qitech_eachismo"><strong>hacka_qitech_eachismo →</strong></a>
* **Pipeline determinístico em 7 etapas**: Validação semântica estrita, consultas externas fora da trava para evitar contenção e lock pessimista atômico (`pg_advisory_xact_lock`) na conta de origem contra rajadas e *race-conditions*.
* **Inteligência de Grafos & Rede Relacional**: Detecção de "vizinhança suja" via busca em largura (BFS até $K=3$ saltos), decaimento exponencial temporal ($\tau = 30$ dias) e penalidade logarítmica de hubs para não penalizar contas legítimas de alto giro (varejo/folha).
* **Fusão de Risco Probabilística (Noisy-OR)**: Combinação independente de 9 famílias de regras (Velocity, Desvio Noturno, Viagem Impossível, DICT/Societário, Log-Normal $Z$-Score), incorporando regra de recorrência (R7) para conceder desconto de fricção a pagamentos habituais.

---

### 📈 Desafio Quant-AI: Itaú Asset
Duas edições do desafio de finanças quantitativas do Itaú Asset: construir um robô trader quantitativo e comprovar seu desempenho com backtests rigorosos.

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>🔵 2026: Janus Reborn</h3>
      <a href="https://github.com/Cerqueira11/Quant-AI-Janus-Reborn"><strong>Quant-AI-Janus-Reborn →</strong></a>
      <p>Modelo <em>cross-sectional</em> multifatorial de ranking com <em>gradient boosting</em> sobre o Ibovespa. Validação <em>walk-forward</em> purgada, custos calibrados para a B3 e correção estatística contra <em>backtest overfitting</em>.</p>
    </td>
    <td valign="top" width="50%">
      <h3>🟠 2025: Janus</h3>
      <a href="https://github.com/Cerqueira11/quant-ai-janus"><strong>quant-ai-janus →</strong></a>
      <p>Robô com estratégia dual (<em>trend-following</em> e <em>mean-reversion</em>) sobre ações da B3, com filtros de amplitude de mercado para alternar entre regimes.</p>
    </td>
  </tr>
</table>

## 🧰 Outras frentes

**Sistemas Financeiros & Arquitetura**: infraestrutura de core bancário (BaaS) com livro-razão (*ledger*) append-only em partidas dobradas imutáveis, controle estrito de concorrência e conformidade regulatória (BACEN / Res. CMN 4.854/2020).

**Modelagem de Dados & SQL**: modelagem relacional de ponta a ponta (diagramas EER, normalização, constraints de integridade, advisory locks e índices compostos) no PostgreSQL.

**Desenvolvimento de Software**: APIs assíncronas em Python (FastAPI), aplicações mobile em Flutter, serviços em Node.js e fundamentos de baixo nível (manipulação de arquivos em disco e memória) em C/C++.

## 🛠️ Stack

**Linguagens**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

**Backend & Infra**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Dados & Quant**  
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/Gradient_Boosting-02569B?style=flat&logo=lightning&logoColor=white)
