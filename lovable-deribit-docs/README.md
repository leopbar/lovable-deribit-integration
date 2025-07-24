# Lovable ⇄ Deribit Integration

Este projeto integra uma interface Lovable com a API da Deribit, permitindo envio de ordens para mercado de derivativos de criptomoedas.

## 🔹 Tecnologias
- Lovable (Frontend React)
- Supabase (Edge Functions + PostgreSQL)
- Deribit API (JSON-RPC)
- Docusaurus para documentação
- GitHub Actions (CI/CD)

## 🔹 Como rodar
1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/lovable-deribit-integration.git
   ```
2. Configure as variáveis de ambiente:
   ```
   SUPABASE_URL=
   SUPABASE_SERVICE_ROLE_KEY=
   DERIBIT_API_KEY=
   DERIBIT_API_SECRET=
   ```
3. Deploy Supabase Functions:
   ```bash
   supabase functions deploy execute-order
   ```

📚 Documentação completa: [Clique aqui](./DOCUMENTACAO_TECNICA.md)
