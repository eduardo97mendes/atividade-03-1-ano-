# 🐾 Atividade 03 · 1º ano · Landing Page EducaCão (HTML5 e CSS3)

> 📅 **Prazo de entrega: de 30/11 a 04/12.** Trabalhos entregues depois de 04/12 não serão aceitos.

## ⚠️ O que você precisa fazer

| Arquivo | Sua tarefa |
| --- | --- |
| `index.html` | **Preencher** todos os `___` com os textos do `modelo.pdf` (inclusive os `alt` das imagens). |
| `css/style.css` | **Responder** cada propriedade: leia as opções A, B e C e digite o valor certo depois dos `:`. |
| `css/base.css` | **Não mexer.** |

Os arquivos já estão soltos neste repositório, **não precisa descompactar nada dentro de outra pasta**.

**PASSO 1:** Clique no botão verde **Code** → **Download ZIP**.

**PASSO 2:** Extraia o ZIP baixado (botão direito → **Extrair tudo**) dentro da sua pasta.

**PASSO 3:** No **VS Code**: **Arquivo → Abrir Pasta** e escolha a pasta extraída (a que tem `index.html`, `css`, `img` e `modelo.pdf`).

**PASSO 4:** Abra o `index.html` com o **Live Server** e comece pelo HTML; depois responda o `style.css` de cima para baixo.

---


> **Você é o(a) desenvolvedor(a) contratado(a) pela EducaCão**, uma empresa fictícia de educação canina. O cliente entregou o arquivo **`modelo.pdf`**, que deve ser reproduzido visualmente no projeto final. Sua missão é montar os textos no HTML e reconstruir o visual com as alternativas do CSS.

## 📘 Versão com explicação (para tirar dúvidas)

Na pasta **`explicacao/`** está a **versão com explicação** para você entender cada parte:

- **`Explicacao_HTML_CSS.pdf`**: a correção da página na ordem do projeto, com o código de cada seção e desenhos explicando cada propriedade do CSS.

Ela mostra as respostas, mas o objetivo é **entender**: tente primeiro, use o PDF quando travar e confira o porquê de cada valor. A pasta `explicacao/` não precisa ir para o seu repositório de entrega.

## 🎯 Objetivo e resultado esperado

A página final deverá apresentar a **mesma organização e a mesma identidade visual do PDF**: marca em verde com destaque laranja, menu horizontal, banner com foto, três cartões de serviços, seção Sobre, faixa verde-clara de diferenciais, três depoimentos fictícios, contato com formulário e rodapé verde-escuro. Primeiro deixe a página **igual ao modelo**; depois você pode **personalizar** (veja a seção 🎨 abaixo), desde que o resultado continue parecido com a landing page do modelo.

Em `css/style.css`, **uma das três opções de cada questão corresponde ao estilo do modelo**. Os valores precisam ser descobertos observando o PDF, testando e comparando. A resposta correta **não está marcada**.

## 📁 Estrutura obrigatória

```text
Atividade-03-Educacao/
├── index.html                ← complete os ___ do HTML
├── modelo.pdf                ← referência visual do cliente
├── README.md                 ← instruções e regras
├── explicacao/               ← PDF(s) com a explicação (para tirar dúvidas)
├── css/
│   ├── base.css              ← base neutra para a visualização (NÃO EDITAR)
│   └── style.css             ← SEU EXERCÍCIO: preencher alternativas
└── img/
    ├── golden.avif
    ├── adestrador1.avif
    ├── adestrador2.avif
    ├── adestrador 3.avif
    └── sobre.jpg
```

**Atenção às imagens:** as quatro fotos `*.avif` neste pacote são recortes da referência entregue pelo professor e servem ao exercício. A foto `sobre.jpg` é apenas um espaço reservado: substitua-a por uma foto apropriada, se disponibilizada pelo professor. Preserve os nomes exatos ou atualize os `src` no HTML. Não use uma pasta `img` vazia.

## 🚀 Como abrir no VS Code e ver tudo acontecendo

1. No GitHub, clique em **Code → Download ZIP**.
2. Extraia **toda a pasta**. Não abra somente o `index.html` sem as pastas `css` e `img`.
3. No **VS Code**, use **Arquivo → Abrir Pasta** e escolha o diretório completo.
4. Instale a extensão **Live Server**, se ainda não estiver instalada.
5. Abra `index.html` e clique com o botão direito em **Open with Live Server**.
6. Deixe o navegador ao lado do VS Code. Preencha uma propriedade, aperte **Ctrl + S** e observe imediatamente a mudança. Use **Ctrl + F** para encontrar o seletor no CSS.
7. Compare o navegador com a página correspondente do `modelo.pdf`, revise e só então avance.

> **A página já aparece no início com um visual neutro**, graças ao arquivo `base.css`. Isso é proposital: o design final só surgirá à medida que o aluno preencher `style.css`.

## 🧩 Regras obrigatórias da atividade

1. **Não edite o `css/base.css`**. Ele existe apenas para você enxergar a evolução do trabalho.
2. **Preencha o `css/style.css` de cima para baixo**. Comece pelas variáveis em `:root` (cores e tamanhos), depois `body`, cabeçalho, logo, menu, botões, banner, serviços e demais seções.
3. Em cada propriedade do CSS, **leia as opções A, B e C** e digite **o valor completo escolhido** depois dos `:`. Ex.: `display: flex;`. **Não escreva `display: A;`**.
4. **Não remova o ponto e vírgula (`;`), as chaves `{ }`, os seletores, os comentários explicativos e os blocos `@media`.**
5. **Não adicione regras no final do CSS para esconder erros** e não substitua `style.css` por um CSS pronto. A atividade exige experimentar, corrigir e compreender os comandos.
6. No `index.html`, **substitua todos os `___` por textos coerentes com o PDF** (depois você pode adaptar os textos), preservando tags, classes, IDs e caminhos das imagens. Não mude o `href` dos links de navegação.
7. Respeite a ordem de importação: no `<head>`, **`base.css` antes de `style.css`**. Não inverta e não apague as duas linhas.
8. **Preserve a estrutura e o layout do PDF**: mesmas seções, na mesma ordem e com a mesma organização. Cores, imagens e textos podem ser personalizados (seção 🎨).
9. **Teste a página no computador e no celular** (F12 → alternar dispositivo). Ajuste as opções dentro dos blocos `@media` para caber corretamente.
10. Os depoimentos são **fictícios**; mantenha essa identificação. O formulário é **apenas demonstrativo**, sem PHP/banco de dados nesta etapa.

### Exemplo de preenchimento

```css
/* display: controla como o elemento se organiza.
   A) block
   B) flex
   C) grid
*/
display: ;          /* ANTES: ainda sem resposta */
```

Escolhendo `flex`, o aluno deverá deixar exatamente:

```css
display: flex;      /* DEPOIS: um valor CSS, não a letra B */
```

**Observação importante sobre as variáveis:** preencher `background: var(--green);` só mostrará a cor esperada depois que `--green` tiver um valor válido em `:root`. Por isso, comece pela paleta; não significa que a ligação do CSS esteja quebrada.

## 🎨 Personalização (depois de ficar igual ao modelo)

Com a página **pronta e igual ao `modelo.pdf`**, você pode deixar com a sua cara:

| Pode mudar ✅ | Não pode mudar ❌ |
| --- | --- |
| Os **valores das cores** no `:root` (`--green`, `--orange`, `--cream`...) | A estrutura do HTML: tags, classes, IDs e a ordem das seções |
| As **imagens** da pasta `img/` (mesmo nome do arquivo, ou ajuste o `src`) | Os `display`, `grid`, `flex` e tamanhos que montam o layout |
| Os **textos** (nome da empresa, serviços, depoimentos), mantendo o tema | Os blocos `@media` (a versão celular tem que continuar funcionando) |
| O texto alternativo `alt` das imagens novas | Os arquivos `base.css` e a ordem dos `<link>` no `<head>` |

O resultado final tem que continuar **parecido com a landing page do modelo**: menu, banner, três serviços, Sobre, diferenciais, depoimentos, contato e rodapé, na mesma organização.

## 🗺️ Ordem de trabalho recomendada

| Etapa | Seção no HTML / CSS | Observe no navegador |
| --- | --- | --- |
| 1 | `:root`, `body`, `img`, `a`, `ul` | Cores, fonte, margens e imagens |
| 2 | `.site-header`, `.logo`, `.main-nav` | Cabeçalho e menu distribuídos |
| 3 | `.button`, `.button-primary`, `.button-secondary` | Botões laranja e verde |
| 4 | `.hero`, `.hero-content`, `.hero-image` | Banner com texto e foto lado a lado |
| 5 | `.section`, `.services`, `.service-grid`, `.service-card` | Três cartões em linha em tela grande |
| 6 | `.about`, `.benefits`, `.benefit-grid` | História e faixa verde-clara |
| 7 | `.testimonial-grid`, `.contact`, `.contact-form` | Depoimentos e formulário |
| 8 | `.site-footer`, `.social-links` | Rodapé verde-escuro |
| 9 | `@media` de 980px e 700px | Versão responsiva |

## 🔧 Se você preencher e não aparecer

- Confira se **salvou com Ctrl+S** e se o Live Server está aberto.
- Verifique o arquivo certo: edite **`css/style.css`**, não `css/base.css`.
- Confirme se o HTML contém **duas** referências a CSS e se a ordem está correta.
- Ao usar `var(--nome)`, confira se a variável do `:root` já foi preenchida corretamente.
- Confira se a propriedade tem `:` e `;` e se as chaves `}` dos blocos estão equilibradas.
- No navegador, use **F12 → Network** e verifique se CSS e imagens não apresentam erro **404**.
- O comando correto pode produzir uma mudança pequena ou só ser visível ao passar o mouse (`:hover`) ou em tela pequena (`@media`).
- Use **Ctrl + Shift + R** para atualizar sem cache, se necessário.

## ✅ Entrega e critérios de avaliação

📅 **Entregar entre 30/11 e 04/12.**

Entregue a pasta ou publique o trabalho no **seu repositório do GitHub** com:

- [ ] `index.html` com todos os textos e atributos `alt` preenchidos;
- [ ] `css/style.css` com as alternativas resolvidas, sem `: ;` nas declarações;
- [ ] `css/base.css` preservado, sem mudanças;
- [ ] imagens da pasta `img/` carregando corretamente;
- [ ] composição e organização parecidas com as duas páginas de `modelo.pdf` (cores e imagens podem ser personalizadas);
- [ ] alinhamento correto de menu, três serviços, diferenciais, depoimentos, formulário e rodapé;
- [ ] versão responsiva testada no celular;
- [ ] imagem da página pronta (captura de tela) comparada ao PDF.


### 📤 Como postar no GitHub e me avisar

**1. Crie o seu repositório**
1. Entre na sua conta do GitHub e clique em **+** (canto superior direito) → **New repository**.
2. Nome sugerido: `atividade-03-educacao-SEU-NOME`. Marque **Public** e clique em **Create repository**.

**2. Envie a pasta do projeto**
1. No repositório novo, clique em **uploading an existing file** (ou **Add file → Upload files**).
2. Abra a pasta do projeto no computador, selecione **tudo o que está dentro dela** (`index.html`, `css`, `img`, ...) e **arraste** para a página do GitHub.
3. Confira se as pastas `css` e `img` apareceram na lista e clique em **Commit changes**.

**3. Me avise abrindo uma Issue (eu recebo notificação)**
1. Abra: **https://github.com/eduardo97mendes/atividade-03-1-ano-/issues/new**
2. **Título:** `Entrega Atividade 03 - Seu Nome Completo - 1º ano`.
3. **Texto:** cole o **link do seu repositório**, escreva **@eduardo97mendes** e, se quiser, arraste uma captura de tela da página pronta.
4. Clique em **Submit new issue** (ou **Create**).

> Escrever `@eduardo97mendes` **dentro da Issue** faz chegar uma notificação para mim. Escrever o @ só no README do seu repositório **não** notifica. Se não conseguir abrir a Issue, mande o link do seu repositório pelo canal da turma.

---

**Próximas etapas:** em aulas futuras poderão ser acrescentados JavaScript, PHP e PostgreSQL, mas **não fazem parte desta entrega de HTML/CSS**.
