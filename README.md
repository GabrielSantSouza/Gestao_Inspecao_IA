Sistema de Inspeção Industrial com Inteligência Artificial

Este projeto é uma solução Full-Stack robusta desenhada para otimizar a manutenção industrial através da análise preditiva de anomalias em equipamentos, utilizando a capacidade de raciocínio do modelo Gemini (Google).

🏭 Visão Geral

A aplicação permite que técnicos de manutenção registem falhas ou comportamentos anormais em máquinas da fábrica através de uma interface intuitiva. O sistema processa estas descrições e gera diretrizes de manutenção corretiva/preventiva em tempo real.

🛠 Arquitetura do Sistema

O sistema está estruturado em microsserviços para garantir escalabilidade:

Frontend: Angular (TypeScript) com Tailwind CSS para uma interface responsiva e moderna.

Backend: Java (Spring Boot) gerindo o histórico de inspeções, persistência de dados e orquestração.

Motor de IA: Python (FastAPI/Uvicorn) responsável por integrar com a API do Google Gemini.

🚀 Como Executar

Pré-requisitos

Java 17+ / Maven

Node.js (v18+) e Angular CLI

Python 3.10+

Passos de Instalação

Clonar o repositório:

git clone <link-do-seu-repo>
cd nome-do-projeto


Iniciar o Backend (Java):

mvn spring-boot:run


Iniciar o Frontend (Angular):

cd frontend
npm install
ng serve


💡 Funcionalidades Principais

Registo Técnico: Interface otimizada para inserção rápida de anomalias.

Dashboard de Gestão: Painel de supervisão com métricas de equipamentos em risco.

Análise Inteligente: Integração direta com IA para diagnóstico técnico imediato.
