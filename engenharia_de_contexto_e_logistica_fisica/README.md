# 🌍 Engenharia de Contexto e Logística Física

## 📝 Descrição do Projeto
Este projeto apresenta soluções algorítmicas desenvolvidas em Python para a análise de dados ambientais e simulação de processos logísticos de segurança. O foco principal é a transformação de variáveis brutas do mundo real em indicadores de tomada de decisão, como índices de conforto e rotas de evacuação eficiente.

O sistema está estruturado no arquivo `engenharia_de_contexto_e_logistica_fisica.py`[cite: 1] e aborda dois pilares fundamentais:
1.  **Monitoramento Urbano:** Processamento de microclimas locais para diagnóstico de qualidade de vida[cite: 1].
2.  **Logística de Emergência:** Simulação de navegação autônoma em cenários de risco, considerando restrições de recursos e obstáculos físicos[cite: 1].

## 🚀 Tecnologias Utilizadas
*   **Linguagem:** Python 3.10+ (utilizando a estrutura `match-case` para classificação de dados)[cite: 1].
*   **Ambiente de Desenvolvimento:** Google Colab e scripts standalone[cite: 1].
*   **Paradigma:** Lógica condicional avançada e máquinas de estados simples[cite: 1].

## 📊 Módulos e Funcionalidades

### 1. Algoritmo de Microclima Local
Este módulo processa uma lista de dados contendo local, horário, temperatura, umidade e o Índice de Qualidade do Ar (IQA)[cite: 1].
*   **Classificação de IQA:** Converte valores numéricos em categorias qualitativas (Boa, Moderada, Ruim ou Muito Ruim)[cite: 1].
*   **Nota de Conforto Urbano:** Calcula uma pontuação de 0 a 10 baseada em penalidades climáticas (ex: temperaturas > 30°C ou umidade < 40% reduzem a nota)[cite: 1].

### 2. Navegação e Evacuação Espacial
Simula o trajeto de um agente por diversos compartimentos (Quarto, Corredor, Sala, etc.) até a saída de segurança (Rua)[cite: 1].
*   **Gestão de Recursos:** O agente inicia com 8 unidades de energia, que são consumidas conforme o esforço de movimentação ou exposição a perigos como fumaça[cite: 1].
*   **Lógica de Inventário:** Implementa a necessidade de encontrar e portar uma chave para transpor portas trancadas no trajeto[cite: 1].
*   **Resiliência:** O sistema prevê o fracasso da missão caso a energia se esgote antes do objetivo final[cite: 1].

## 🔧 Como Executar
1.  Certifique-se de ter o **Python 3.10** ou superior instalado.
2.  Clone este repositório em sua máquina local.
3.  Execute o script principal para visualizar os testes automatizados no console:
    ```bash
    python engenharia_de_contexto_e_logistica_fisica.py
    ```
[Voltar ao início](https://github.com/vinischerer08-hub/portifolio-vinicius-scherer-di-giorno)
