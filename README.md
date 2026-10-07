# Receitas do Iuri — imagens dos drinks

Este site funciona no GitHub Pages. Para trocar os desenhos/ícones pelas fotos dos drinks, **não é necessário editar o `index.html`**. Basta adicionar as imagens à pasta `imagens` do repositório.

## 1. Estrutura das pastas

```text
receitas-do-iuri/
├── index.html
├── README.md
└── imagens/
    ├── caipirinha.jpg
    ├── mojito.webp
    ├── negroni.png
    └── gin-tonica.jpeg
```

A pasta **`imagens`** deve ficar na mesma altura do arquivo `index.html`, com esse nome exatamente (tudo minúsculo).

## 2. Como nomear as fotos

O nome precisa corresponder ao **nome da receita mostrado no site**, seguindo estas regras:

- Use **letras minúsculas**.
- Tire os **acentos**: `Piña` → `pina`.
- Troque **espaços e pontuação por hífens**: `Gin Tônica` → `gin-tonica`.
- Não use espaços no nome do arquivo.

**Exemplos**

| Nome da receita | Nome do arquivo |
|---|---|
| Caipirinha | `caipirinha.jpg` |
| Mojito | `mojito.webp` |
| Gin Tônica | `gin-tonica.png` |
| Piña Colada | `pina-colada.jpg` |
| Old Fashioned | `old-fashioned.jpeg` |
| Moscow Mule | `moscow-mule.webp` |

**Formatos aceitos:** `.webp`, `.jpg`, `.jpeg` e `.png` (nessa ordem de prioridade, caso existam várias fotos com o mesmo nome).

## 3. Como adicionar uma foto pelo GitHub

1. Abra o repositório `receitas-do-iuri` no GitHub.
2. Entre na pasta `imagens`.
3. Clique em **Add file → Upload files**.
4. Escolha as fotos, já com os nomes corretos.
5. Clique em **Commit changes**.
6. Aguarde o GitHub Pages atualizar e recarregue o site.

Você pode adicionar as fotos aos poucos. **Se não existir uma imagem válida para o drink, o site mantém o visual alternativo atual (ícone/desenho).**

## 4. Como trocar uma foto

Envie outra imagem com **o mesmo nome e extensão**, substituindo o arquivo anterior no repositório. Se o navegador continuar mostrando a imagem antiga, atualize a página forçando o recarregamento (no computador: `Ctrl + F5`) ou aguarde o cache atualizar.

## 5. Dicas para ficar bonito e rápido

- Prefira fotos **verticais ou quadradas**, com o drink no centro.
- Uma largura de **800 a 1200 pixels** costuma ser suficiente.
- Prefira `.webp` para arquivos menores; tente manter cada foto abaixo de **300 KB**, quando possível.
- Use fotos suas ou imagens que você tenha permissão para reutilizar, especialmente se o repositório/site for público.
- Coloque o **arquivo da imagem** na pasta `imagens`, não um link de página da internet.

## 6. Se a foto não aparecer

Verifique se: (1) a pasta é `imagens`, (2) o nome corresponde exatamente ao drink convertido para minúsculas e hífens, (3) a extensão é aceita, (4) o upload foi confirmado e (5) o GitHub Pages já publicou a alteração.

> Observação: o GitHub diferencia maiúsculas de minúsculas nos caminhos dos arquivos. `Caipirinha.JPG` não é igual a `caipirinha.jpg`.
