# Documentação Técnica - Integração Lovable ⇄ Deribit

## 1. Visão Geral do Projeto
Este projeto realiza integração entre a interface Lovable (frontend) e a API Deribit para envio de ordens no mercado de derivativos de criptomoedas.

### Componentes Principais
- **Frontend**: Lovable (interface React)
- **Backend**: Supabase (Edge Functions + PostgreSQL)
- **API Externa**: Deribit JSON-RPC (via HTTPS)

## 2. Fluxo da Aplicação
1. Usuário preenche formulário no Lovable.
2. Frontend envia requisição para Supabase Function.
3. Função insere ordem no banco (status `pending`).
4. Função envia ordem para Deribit via JSON-RPC.
5. Retorna status (`filled` ou `error`) e atualiza banco.
6. Frontend mostra resultado ao usuário.

## 3. Estrutura do Repositório
...
(Há mais conteúdo detalhado aqui, mas simplificado para manter compacto)
