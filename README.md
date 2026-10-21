# CRM Diego Dias

CRM responsivo em HTML, CSS e JavaScript para organizar clientes, funil de vendas, retornos, cobranças e mensagens prontas para WhatsApp.

## Como usar
1. Abra `index.html` no navegador ou publique o repositório com GitHub Pages.
2. Cadastre clientes usando o telefone com código do país e DDD, apenas números (ex.: `5591999999999`).
3. Use o botão WhatsApp para abrir `wa.me` com uma mensagem preenchida.
4. Registre cobranças e marque-as como pagas após confirmar o recebimento.
5. Exporte um backup JSON em **Configurações** periodicamente.

## Publicar com GitHub Pages
1. No repositório, abra **Settings**.
2. Entre em **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)), depois salve.
5. Aguarde a publicação. O endereço esperado é https://diascliente95-wq.github.io/CRM-Diego-Dias/

## Limitações importantes
- Esta versão salva os dados no armazenamento local do navegador. Não sincroniza automaticamente entre dispositivos nem possui login ou banco de dados central.
- Os links `wa.me` abrem o WhatsApp com texto preenchido; não leem conversas nem enviam mensagens automaticamente.
- Os dados do CRM podem ser sensíveis. Use um dispositivo protegido e faça backups com segurança.
- Para uso por várias pessoas, autenticação, sincronização e armazenamento seguro, será necessário integrar um backend e um banco de dados.
