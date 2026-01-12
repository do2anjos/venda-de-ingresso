# Loja de Ingressos com "Timer"

**Tema:** A Loja de Ingressos com "Timer". 
**Stack:** C# .NET / Angular .NET

---

## Contexto
Um mini sistema de venda de ingressos para um cinema pequeno.

---

## Stack's

### Backend
- **C# .NET**
- **Entity Framework Core** 
- **SQL Server 2022**

### Frontend
- **Angular 21** 
- **TypeScript**
- **SCSS**

---

## O Desafio

O usuário seleciona um assento num mapa visual da sala e finaliza a "compra". 

1. **Timer de Reserva:** Quando o usuário clica no assento, ele fica "Reservado" para ele por apenas **2 minutos**. Se ele não confirmar a compra (botão final) nesse tempo, o assento volta a ficar livre automaticamente.
2. **Regra de Vizinhança:** O sistema não pode permitir que um usuário compre um assento que esteja imediatamente ao lado de um assento já ocupado, a menos que comprem juntos. 
3. **Feedback Visual:** O mapa da sala deve atualizar as cores (**Livre**, **Selecionado**, **Ocupado**).

---

## Como Executar

### Pré-requisitos
- .NET 10 SDK (ou superior)
- Node.js (v18+)
- Angular CLI

### Passos
1. **Backend:**
   ```bash
   cd "venda de ingresso.Api"
   dotnet restore
   dotnet run
   ```

2. **Frontend:**
   ```bash
   cd "venda de ingresso Front"
   npm install
   ng start
   ```
3. Acesse em `http://localhost:4200`

---
