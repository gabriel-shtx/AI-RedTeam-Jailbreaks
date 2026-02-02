# AI – Red Teaming

## 📌 Introdução

Este repositório é minha contribuição para a comunidade de **Red Teamers**, com foco em **simulação de adversários em IAs (LLMs)**.

O material aqui reunido é resultado de **anotações, estudos e experimentos práticos**, baseados em conteúdos públicos encontrados na internet e em **testes reais realizados contra diferentes modelos de linguagem**. O foco não é teoria abstrata, mas sim **o que funcionou na prática** durante avaliações de comportamento e resiliência de IAs.

O objetivo principal é documentar técnicas, padrões e abordagens que permitam:

* Avaliar limites e restrições de LLMs
* Simular comportamentos adversariais
* Identificar falhas de alinhamento
* Explorar técnicas de **jailbreak** sob a ótica de Red Team

---

## 🎯 Objetivo do Repositório

Este repositório tem caráter **educacional e de pesquisa**, sendo voltado para:

* Profissionais de **Red Team**
* Pesquisadores em **Segurança de IA**
* Pessoas interessadas em **LLM Security, Prompt Injection e Adversarial Testing**

O conteúdo aqui apresentado deve ser utilizado **exclusivamente para fins de estudo, pesquisa e fortalecimento da segurança de sistemas baseados em IA**.

---

## 🧠 Metodologias Abordadas

Abaixo estão as principais metodologias e técnicas que serão documentadas neste repositório.

### 🔹 Jailbreak via Crescendo

Técnica baseada em **escalonamento progressivo de contexto**, onde o prompt começa de forma inofensiva e, gradualmente, conduz o modelo a estados de resposta mais permissivos.

Essa abordagem explora:

* Acúmulo de contexto
* Confiança progressiva do modelo
* Quebra gradual de restrições

---

### 🔹 Skeleton Key

Metodologia que utiliza **estruturas-base (esqueletos de instruções)** para induzir o modelo a aceitar comandos sensíveis como parte de um processo maior, legítimo ou técnico.

Muito eficaz para:

* Bypass de filtros diretos
* Reformulação de intenções proibidas
* Engenharia de prompts complexos

---

### 🔹 Prompt Injection

Exploração de falhas na interpretação de instruções do modelo, manipulando entradas para **subverter regras, políticas ou contexto previamente definido**.

Inclui cenários como:

* Injeção direta
* Injeção indireta
* Quebra de contexto
* Conflito de instruções

---

### 🔹 Persona e Personalidade

Criação e manipulação de **personas artificiais** para alterar o comportamento do modelo, levando-o a agir fora de suas restrições normais.

Essa técnica explora:

* Roleplay avançado
* Desvio de alinhamento
* Contextos alternativos de autoridade ou especialização

---

## 🧪 Estrutura do Repositório (em evolução)

A organização do repositório seguirá uma estrutura semelhante a:

```
.
├── crescendo/
├── skeleton-key/
├── prompt-injection/
├── persona-personality/
├── notes/
└── references/
```

Cada diretório conterá:

* Explicação da técnica
* Exemplos de prompts
* Observações práticas
* Limitações e comportamentos observados

---

## ⚠️ Aviso Importante

Este repositório **não incentiva uso malicioso** de técnicas contra sistemas reais sem autorização.

Todas as técnicas documentadas têm como finalidade:

* Pesquisa
* Simulação adversarial
* Melhoria de segurança
* Conscientização sobre riscos em LLMs

Utilize este conteúdo de forma **ética e responsável**.

---

## 🤝 Contribuições

Sugestões, correções e contribuições são bem-vindas, desde que alinhadas com o propósito educacional e de pesquisa do projeto.

---

## 📚 Referências

As referências utilizadas serão adicionadas progressivamente ao longo do repositório, sempre que aplicável.

---

🧠 *Think like an adversary. Build safer AI.*
