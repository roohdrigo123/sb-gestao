# SB Gestão
Sistema web responsivo para agenda, clientes, orçamentos, OS, financeiro, obras e fotos da SB Serviços Gerais.

## Como publicar na Vercel
1. Suba todos os arquivos para um repositório GitHub chamado `sb-gestao`.
2. Na Vercel, clique em Add New > Project.
3. Importe o repositório.
4. Deploy.

## Supabase
O sistema abre em modo demonstração sem Supabase. Para ativar login real:
1. Crie projeto no Supabase.
2. Copie Project URL e anon public key.
3. Na Vercel, vá em Settings > Environment Variables.
4. Adicione:
- VITE_SUPABASE_URL
- VITE_SUPABASE_ANON_KEY
