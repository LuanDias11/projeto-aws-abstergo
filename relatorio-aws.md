# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 13/01/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Luan França Dias

---

## 1. Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Luan França Dias**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimização de recursos em nuvem.

## 2. Descrição do Projeto
O projeto de implementação foi focado em eficiência financeira e automação de recursos. Abaixo, detalhamos as ferramentas escolhidas:

### Etapa 1: AWS Lambda
* **Foco:** Computação Serverless (Sem servidor).
* **Caso de uso:** Substituição de servidores EC2 ligados 24/7 para tarefas esporádicas. A empresa passa a pagar apenas pelo tempo de execução, eliminando custos de ociosidade.

### Etapa 2: Amazon S3 Intelligent-Tiering
* **Foco:** Otimização de custos de armazenamento.
* **Caso de uso:** Movimentação automática de arquivos para camadas de acesso menos frequente (mais baratas), reduzindo a fatura de storage sem impacto na disponibilidade.

### Etapa 3: AWS Budget & Cost Explorer
* **Foco:** Monitoramento e governança financeira.
* **Caso de uso:** Criação de alertas de gastos em tempo real e análise de tendências para evitar surpresas na fatura e identificar recursos subutilizados.

---

## 3. Conclusão
A implementação dessas ferramentas na **Abstergo Industries** visa a redução direta de desperdícios e a automação da gestão de custos. Espera-se uma operação mais enxuta, aumentando a eficiência e a previsibilidade financeira.

**Recomendações futuras:**
* Implementação de Instâncias Spot para ambientes de teste.
* Revisão trimestral das políticas de ciclo de vida do S3.

---
*Relatório gerado para fins de documentação de infraestrutura cloud.*
