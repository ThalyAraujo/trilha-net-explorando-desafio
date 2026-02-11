# 🏨 Sistema de Hospedagem — Desafio .NET (DIO)

Projeto desenvolvido como desafio prático da trilha **.NET — Explorando a linguagem C#** da plataforma @DIO.

O objetivo foi implementar regras de negócio para um sistema simples de hospedagem, aplicando conceitos de orientação a objetos, validações e cálculos condicionais.

---

## 🎯 Objetivo do Desafio

Construir a lógica de um sistema de reservas de hotel utilizando C#, relacionando as classes:

- Pessoa (hóspede)
- Suite
- Reserva

Implementando validações e regras de cálculo conforme os requisitos propostos.

---

## 🧠 Regras Implementadas

✅ Não permite cadastrar hóspedes acima da capacidade da suíte  
✅ Retorna corretamente a quantidade de hóspedes cadastrados  
✅ Calcula o valor total da reserva  
✅ Aplica **10% de desconto** para reservas com 10 dias ou mais  
✅ Lança exceção quando a capacidade é excedida  
✅ Organização da lógica de negócio na classe `Reserva`

---

## 💻 Conceitos Praticados

- Programação Orientada a Objetos (POO)
- Relacionamento entre classes
- Listas (`List<T>`)
- Validações de regra de negócio
- Tratamento de exceções
- Cálculo com regras condicionais
- Organização de código
- Versionamento com Git

---

## 📂 Estrutura do Projeto

```DesafioProjetoHospedagem/
├── Models/
│ ├── Pessoa.cs
│ ├── Suite.cs
│ └── Reserva.cs
└── Program.cs
```
---

## ▶️ Como Executar

É necessário ter o **.NET SDK** instalado.

No terminal, dentro da pasta do projeto:

```bash
dotnet run
