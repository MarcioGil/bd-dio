# 📘 Desafio DIO: Criando um Banco de Dados SQL no Microsoft Azure

Este repositório documenta minha experiência na criação e configuração de um **Banco de Dados SQL na plataforma Microsoft Azure**, como parte do desafio proposto pela [Digital Innovation One (DIO)](https://www.dio.me/).

---

## 🚀 Objetivo do Desafio

- Praticar o processo de configuração de uma instância de Banco de Dados SQL no Azure.  
- Documentar os passos realizados e as decisões tomadas durante o processo.  
- Criar um material de apoio com resumos, anotações e dicas úteis.  
- Utilizar o GitHub para compartilhar a documentação técnica.  

---

## 🛠️ Etapas Realizadas

1. **Acesso ao Portal do Azure**  
   - Entrei no [Azure Portal](https://portal.azure.com) com minha conta.  

2. **Criação do Banco de Dados SQL**  
   - Nome do banco de dados definido: `BancoDio`  
   - Servidor criado/região: *Brazil South*  
   - Tipo de uso elástico: **Não**  
   - Ambiente de carga de trabalho: **Desenvolvimento**  

3. **Configurações de Computação e Armazenamento**  
   - Plano escolhido: **Uso Geral (Gen5, 2 vCores, 32 GB de armazenamento)**  
   - Zona redundante: **Desabilitada**  

4. **Revisão e Criação**  
   - Após configurar, revisei os detalhes e criei o recurso.  
   - Aguardei o provisionamento e confirmei que o banco estava ativo.  

---

## 💡 Dicas Importantes

- **Região:** escolher sempre a mais próxima (ex.: *Brazil South*) reduz latência.  
- **Elastic Pool:** útil em ambientes corporativos com vários bancos de dados. Para estudos, pode ser desmarcado.  
- **Produção vs Desenvolvimento:** para testes e aprendizado, use **Desenvolvimento**.  
- **Documentação Oficial:** [Guia Rápido do Azure SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal).  

---

## 📂 Estrutura do Repositório

📦 desafio-azure-sql
┣ 📂 images # prints das etapas (opcional)
┗ 📜 README.md # documentação principal

---

## ✅ Conclusão

Este desafio permitiu praticar a criação de um Banco de Dados SQL no **Microsoft Azure**, reforçando os conceitos aprendidos durante as aulas e servindo como base para futuros estudos em **banco de dados em nuvem**.

---

👉 Próxima etapa: conectar o banco de dados criado via **Azure Data Studio** ou **SQL Server Management Studio (SSMS)** para testar consultas.
