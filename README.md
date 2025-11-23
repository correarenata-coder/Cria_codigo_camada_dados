# 🧩 Criação Automática da Camada de Dados (MVC + Dapper)

Este projeto foi desenvolvido para ajudar desenvolvedores iniciantes a gerar automaticamente a camada de dados de um projeto MVC, a partir do nome da tabela e de seus respectivos campos.

---

## 🎯 Objetivo do Projeto

Facilitar e agilizar a criação da camada de dados, oferecendo suporte especialmente para profissionais que estão iniciando na área de tecnologia.

---

## 🛠️ Como Funciona

O agente é muito simples de usar:  
Basta informar:
- Nome da tabela  
- Lista de campos  
- Tipo de cada campo  

Com base nisso, ele gerará automaticamente todo o código necessário em **C#**, utilizando **MVC** e **Dapper**.

------------------------------------------------------------------------

# 🚀 Passo a Passo Completo

## 📌 1 --- Criar o Resource Group

Acesse o portal e crie um Resource Group para organizar os recursos do
projeto.

<img width="798" height="421" alt="TELA_01" src="https://github.com/user-attachments/assets/8129ab57-af03-47aa-a4b3-446a9ee16bc5" />


<img width="821" height="553" alt="TELA_02" src="https://github.com/user-attachments/assets/6b9aec4b-c3f3-4c41-8979-b5e26a9e1886" />

------------------------------------------------------------------------

## 🤖 2 --- Acessar o Portal do AI Foundry

Entre no **AI Foundry** para criação do modelo de IA que será utilizado.

<img width="894" height="528" alt="TELA_04" src="https://github.com/user-attachments/assets/e0a0a1f2-11d2-453f-94e6-11507c1aa5f3" />


------------------------------------------------------------------------

## 🧠 3 --- Escolher o Modelo

O modelo utilizado neste projeto foi:

> **gpt-4.1-mini**
<img width="1087" height="857" alt="TELA_05" src="https://github.com/user-attachments/assets/717e40d5-9416-4eed-a532-e6282e9cb663" />


------------------------------------------------------------------------

## 🧪 4 --- Testar o Modelo no Playground

Exemplo de prompt usado:

    Você é um assistente para fazer coquetéis sem álcool, pois é para festa de crianças. Não pode ter nada alcoólico.

<img width="1501" height="869" alt="TELA_06" src="https://github.com/user-attachments/assets/95a01a34-b75f-4066-b8af-e6aa855b58a0" />

<img width="1602" height="644" alt="TELA_07" src="https://github.com/user-attachments/assets/0394149c-490f-4b2f-8366-e44ccc5e6d46" />

<img width="1004" height="278" alt="TELA_08" src="https://github.com/user-attachments/assets/5e215b9b-a343-4300-8af6-3683d2629cf5" />


------------------------------------------------------------------------

## 🛠️ 5 --- Criar o Agente "Criação de Código"

Prompt utilizado:

    Você é um assistente de IA que recebe uma estrutura de tabela e ajuda os desenvolvedores a fazerem a camada de dados em um projeto MVC usando SQL e Dapper.

<img width="1651" height="666" alt="TELA_09" src="https://github.com/user-attachments/assets/f8f7b7ec-d94b-4316-985e-6c0c60371a13" />

------------------------------------------------------------------------

## 🧪 6 --- Testar o Agente

Exemplo:

    Cria tabela ALUNO 
    IDALUNO int (chave), 
    NOMEALUNO varchar(50), 
    NOMEMAE varchar(50), 
    DTNASC

![Descrição da Imagem](TELA_07.png)

------------------------------------------------------------------------

## ⚡ 7 --- Criar uma Ação (Action)

Permite chamar o agente via APIs e automações externas.

![Descrição da Imagem](TELA_08.png)

![Descrição da Imagem](TELA_09.png)

![Descrição da Imagem](TELA_10.png)

------------------------------------------------------------------------

# 🎉 Conclusão

Este projeto mostra como usar **AI Foundry + GPT-4.1-Mini** para
automatizar a criação da camada de dados em **C# MVC com Dapper**,
reduzindo esforço manual, erros comuns e acelerando o aprendizado de
novos desenvolvedores.


## Indicações de materiais

- [What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry)  
