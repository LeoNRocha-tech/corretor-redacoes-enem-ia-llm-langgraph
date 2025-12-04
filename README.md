# **📝 Corretor de Redações ENEM com IA — LLM & LangGraph**

Um sistema inteligente capaz de avaliar redações do ENEM automaticamente, usando **modelos de linguagem (LLMs)** e **LangGraph** para criar um fluxo estruturado de avaliação baseado nas **5 competências oficiais** do exame.

Este projeto é ideal como base para estudo, pesquisa, portfólio e futuras evoluções em IA aplicada à educação.

---

## 🚀 Objetivo do Projeto

Criar um **pipeline automático de correção de redações**, seguindo a metodologia oficial do ENEM:

| Competência | Descrição |
|------------ |-----------|
| **C1** | Domínio da norma culta |
| **C2** | Compreensão da proposta |
| **C3** | Seleção e organização das ideias |
| **C4** | Capacidade argumentativa |
| **C5** | Proposta de intervenção |

Cada competência é avaliada de **0 a 200**, totalizando uma nota final **entre 0 e 1000 pontos**.

---

## 🧠 Tecnologias Utilizadas

- **LangGraph** – para orquestração do fluxo de avaliação  
- **Python 3.10+**  
- **LLMs da OpenAI ou compatíveis**  
- **Structured Outputs**  
- **Prompt Engineering**  

---

📁 Estrutura Inicial do Projeto

```bash
corretor-redacoes-enem-ia-llm-langgraph/
│
├── README.md
├── requirements.txt
│
└── src/
    ├── main.py
    │
    ├── graph/
    │   ├── c1_norma_culta.py
    │   ├── c2_compreensao.py
    │   ├── c3_organizacao.py
    │   ├── c4_argumentacao.py
    │   ├── c5_intervencao.py
    │   └── evaluation_graph.py
    │
    ├── llm/
    │   ├── model.py
    │   └── prompts.py
    │
    └── utils/
        └── helpers.py
│
└── examples/
    └── redacao_exemplo.txt

```

## 🔧 Instalação

1. Clone o repositório

```bash
git clone https://github.com/LeoNRocha-tech/corretor-redacoes-enem-ia-llm-langgraph.git

```
2. Criar ambiente virtual (opcional, recomendado)
python -m venv .venv

3. Instalar dependências
pip install -r requirements.txt

▶️ Como Executar
python src/main.py

No futuro, o script receberá:

um arquivo .txt

ou uma redação fornecida via input

E retornará notas + feedback detalhado para cada competência.

---

## 🚧 Status Atual (Roadmap)

**Fase atual:** Desenvolvimento Inicial

- [x] Estrutura inicial do repositório  
- [x] Definição das competências  
- [ ] Implementação da C1  
- [ ] Implementação da C2  
- [ ] Implementação da C3  
- [ ] Implementação da C4  
- [ ] Implementação da C5  
- [ ] Testes com redações reais  
- [ ] Calibração com correções humanas

---

##🤝 Como Contribuir

Este repositório faz parte de um projeto de aprendizado.
Alunos podem:

criar forks privados

testar competências

melhorar prompts

sugerir melhorias

---

##📜 Licença

Distribuído sob a licença MIT.

---