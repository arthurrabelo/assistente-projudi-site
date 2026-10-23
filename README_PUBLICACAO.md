# Site do Assistente PROJUDI

Site estático (HTML + CSS), sem dependências e sem envio de dados.

## Visualizar localmente
Abra `index.html` no navegador.

## Publicar gratuitamente no GitHub Pages
1. Crie um repositório para o SITE (por exemplo, `assistente-projudi-site`). Não envie o código-fonte do robô.
2. Envie `index.html`, `logo_ap.png` e `interface_aprovada.png` para a raiz do repositório.
3. Em Settings > Pages, escolha Deploy from a branch e a branch `main`, pasta `/ (root)`.
4. Aguarde o endereço público gerado pelo GitHub Pages.

**IMPORTANTE:** A página atual é informativa e o botão de download está desabilitado propositalmente.
Não publique instalador antes de obter autorização institucional e testar a instalação em outro PC.

## Habilitar download após liberação
1. Gere o instalador final da v1.1.0 no Windows e teste-o em um computador limpo.
2. Obtenha autorização para distribuição.
3. Publique o instalador em GitHub Releases ou repositório institucional autorizado.
4. Em `index.html`, substitua o elemento:
   `<button class="btn disabled" disabled aria-disabled="true">🔒 Download aguardando liberação</button>`
   por:
   `<a class="btn primary" href="URL_REAL_DO_INSTALADOR" rel="noopener noreferrer">↓ Baixar para Windows</a>`
   usando a URL real, confirmada, do arquivo publicado.
5. Atualize o texto explicativo da seção Download e a versão, quando necessário.

## Observações
- Não use logomarca oficial do TJGO sem autorização.
- Nunca publique credenciais, perfis de navegador ou dados processuais.
- O site não hospeda o instalador e não coleta dados de visitantes.
- O mockup da interface é ilustrativo; a aparência real depende da versão instalada.

- A prévia usa a imagem do layout aprovado, não um mockup simplificado em HTML.
