# IFTO Map — Mapa Interativo com GPS (Campus Palmas)

Mapa interativo web do **IFTO — Campus Palmas** com busca instantânea de blocos, salas, laboratórios, coordenações e roteamento GPS sobre as passarelas e corredores reais do campus.

## Estrutura do Repositório

- `index.html`: Aplicação web completa (HTML, CSS, JavaScript e base georreferenciada).
- `.nojekyll`: Garante que o GitHub Pages sirva os arquivos estáticos sem processamento Jekyll.
- `README.md`: Documentação do projeto.

## Como publicar no GitHub Pages (sem exibir seu nome pessoal no link)

1. Crie uma **Organização gratuita** no GitHub chamada `ifto-map` (ou `iftomap`).
2. Dentro dessa organização, crie um repositório público chamado **`ifto-map.github.io`** (ou `mapa` caso queira o link `https://ifto-map.github.io/mapa/`).
3. Envie (faça upload) os arquivos deste pacote (`index.html`, `.nojekyll` e `README.md`) para a raiz do repositório.
4. Acesse **Settings → Pages**, selecione a branch **`main`** (pasta **`/ (root)`**) e clique em **Save**.
5. Em instantes, o site ficará no ar em:
   - `https://ifto-map.github.io/` (se o repositório tiver o mesmo nome da organização + `.github.io`)
   - ou `https://ifto-map.github.io/mapa/` (se o repositório se chamar `mapa`).
