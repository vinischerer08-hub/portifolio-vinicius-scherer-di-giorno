# 🏥 Sistema de Triagem de Glicose (Saúde Pública)

## 📝 Descrição do Projeto
Este projeto automatiza o fluxo de triagem inicial em uma unidade de saúde pública, com foco na monitoração dos níveis de glicose dos pacientes[cite: 1, 4, 15]. [cite_start]O objetivo é otimizar o atendimento hospitalar, garantindo que casos críticos recebam intervenção médica imediata enquanto organiza a fila de espera para casos não emergenciais conforme a disponibilidade da unidade[cite: 10, 11, 12, 33].

Desenvolvido para facilitar o processo de recepção, o sistema realiza a coleta de dados básicos (nome e idade) e processa a leitura da glicose para determinar a prioridade do atendimento[cite: 16, 18, 19, 21].


## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python [cite: 13, 18, 20]
* **Lógica de Fluxo:** Estruturas condicionais (If/Else) para triagem de risco [cite: 22, 28]
* **Documentação:** Fluxograma de processos hospitalares [cite: 1]

## 📊 Regras de Negócio e Fluxo
O sistema segue uma lógica de decisão rigorosa baseada nos níveis de glicose detectados no paciente:

* **Coleta de Dados:** O processo inicia com a entrada do nome, idade e o valor da glicose em mg/dL[cite: 16, 18, 20, 25].
* **Nível Crítico (Glicose > 300 mg/dL):** * O sistema dispara um alerta de "Glicose muito alta!"[cite: 6, 22, 23].
    * A equipe médica é acionada imediatamente[cite: 8, 9, 26].
    * O paciente é encaminhado para **atendimento imediato**[cite: 11, 27].
* **Nível Não Crítico:** * O sistema informa que o estado não é crítico[cite: 29].
    * O paciente é orientado a aguardar o atendimento conforme a disponibilidade da equipe[cite: 7, 30, 33].

## 🔧 Como Executar
1. Certifique-se de ter o Python instalado em sua máquina[cite: 13].
2. Clone este repositório.
3. Execute o script principal:
   ```bash
   python sistema_triagem.py

  [Voltar ao início](https://github.com/vinischerer08-hub/portifolio-vinicius-scherer-di-giorno)
