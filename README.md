# 📊 Worker Contracts – Cálculo de rendimento mensal

Projeto desenvolvido em **Java** para praticar **Programação Orientada a Objetos**, simulando o cálculo do salário de um trabalhador com múltiplos contratos por hora.

## 🧩 Funcionalidade
- Cadastro de um trabalhador com nome, nível (Júnior, Pleno, Sênior), salário base e departamento.
- Entrada de N contratos (cada um com data, valor por hora e horas trabalhadas).
- Cálculo do salário de um mês/ano específico (salário base + contratos do mês).

## 🛠️ Conceitos aplicados
- **Encapsulamento:** classes com atributos privados e métodos públicos.
- **Composição:** Worker possui um Department e uma lista de HourContract.
- **Enumerações:** WorkerLevel para os níveis do trabalhador.
- **API java.time:** uso de LocalDate para manipulação de datas.
- **Coleções:** List para armazenar contratos.

## 🚀 Tecnologias
- Java 17
- Maven
- JUnit 5 (testes unitários)
- IntelliJ IDEA

## ✅ Testes
Implementados testes unitários para o método `Worker.income()`, validando cenários com e sem contratos no mês.

## 📦 Como executar
1. Clone o repositório
2. Abra no IntelliJ (ou qualquer IDE Java com suporte a Maven)
3. Execute a classe `Program`
4. Siga as instruções no console.

---
⭐ Se este projeto te ajudou, deixe uma estrela!
