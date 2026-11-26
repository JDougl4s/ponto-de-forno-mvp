# Ponto de Forno — Gestão Inteligente de Produção e Insumos

Aplicação web desenvolvida para pequenas confeitarias, docerias e padarias artesanais planejarem a produção com base no histórico de vendas e encomendas futuras, controlarem o estoque por ficha técnica, registrarem perdas e gerarem listas de compras automáticas.

## Funcionalidades do MVP
- **Painel & Recomendação de Produção:** Calcula a meta ideal de fornada cruzando a média diária de vendas com as encomendas confirmadas.
- **Pedidos & Encomendas:** Registra vendas de balcão e encomendas futuras, atualizando automaticamente a demanda do dia.
- **Estoque & Ficha Técnica:** Controla saldos de matéria-prima, sinaliza insumos abaixo do estoque mínimo e aplica baixa automática por lote produzido.
- **Registro de Perdas:** Registra quebras e desperdícios operacionais em tempo real.
- **Lista de Compras Inteligente:** Calcula a quantidade exata a repor (`Necessidade da Produção + Estoque Mínimo - Estoque Atual`).

## Arquitetura e Tecnologias
- **Frontend:** HTML5, Tailwind CSS e JavaScript (prototipado via Google Stitch)
- **Backend / Banco de Dados:** Supabase (PostgreSQL + API REST)
- **Hospedagem:** Vercel

## Como rodar o projeto
1. Clone este repositório ou baixe os arquivos:
   ```bash
   git clone [https://github.com/JDougl4s/ponto-de-forno-mvp.git](https://github.com/JDougl4s/ponto-de-forno-mvp.git)
