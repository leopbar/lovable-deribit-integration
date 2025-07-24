# Guia Rápido

## 1. Pré-requisitos
- Conta Supabase configurada
- API Key da Deribit
- Node.js instalado

## 2. Clonar projeto
```bash
git clone https://github.com/SEU-USUARIO/lovable-deribit-integration.git
```

## 3. Configurar variáveis
Crie `.env` com:
```
SUPABASE_URL=
SUPABASE_SERVICE_ROLE_KEY=
DERIBIT_API_KEY=
DERIBIT_API_SECRET=
```

## 4. Deploy
```bash
supabase functions deploy execute-order
```
