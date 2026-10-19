# Semana Acadêmica da Phorte (SAP)

Site oficial da Semana Acadêmica da Phorte, evento anual da Faculdade Phorte.

🔗 Site: https://semanaacademicaphortesap.github.io/semana-academica-phorte/

---

## 📁 Estrutura do repositório

```
├── index.html          → página do site
├── og-image.jpg        → imagem de pré-visualização ao compartilhar o link (WhatsApp, redes sociais)
├── sitemap.xml         → mapa do site para o Google (SEO)
├── README.md           → este arquivo
└── fotos/
    ├── 2026/           → fotos da edição de 2026
    ├── 2027/           → fotos da edição de 2027 (criar quando necessário)
    └── ...
```

### Regras para as fotos

- Cada edição tem a sua subpasta dentro de `fotos/`, nomeada com o ano.
- Use **nomes sem espaços, acentos ou caracteres especiais**. Exemplo: `palestra_abertura.jpg`.
- Prefira **letras minúsculas**. O GitHub Pages diferencia maiúsculas de minúsculas: `Foto.jpg` e `foto.jpg` são arquivos diferentes, e um nome diferente do que está no código quebra a imagem no site.
- Fotos de palestrantes: **quadradas, em `.webp`, com cerca de 400 × 400 px**, com o rosto centralizado (elas aparecem dentro de um círculo). Outras fotos podem ser `.jpg` ou `.webp`. Evite arquivos muito pesados, para o site carregar rápido.
- O nome do arquivo precisa ser **idêntico** ao que está no código do `index.html`, incluindo a extensão (`.webp` é diferente de `.jpg`).
- Para usar uma foto no site, aponte para o caminho completo. Exemplo: `<img src="fotos/2026/palestra_abertura.jpg" alt="Descrição da foto">`.

> Observação: as imagens atuais do `index.html` (logos e fundo do topo) estão embutidas no próprio arquivo. Por isso o site funciona sem depender da pasta `fotos/`. Fotos novas podem ser adicionadas pela pasta.

---

## 🔄 Como preparar uma nova edição

1. Crie a pasta do novo ano dentro de `fotos/` (exemplo: `fotos/2027/`) e envie as novas imagens.
2. No `index.html`, atualize datas, programação, palestrantes e os caminhos das imagens (trocando o ano da pasta).
3. Atualize as informações de compartilhamento no `<head>` do `index.html`: título, descrição, datas e o bloco de dados estruturados (SEO).
4. Atualize a data (`lastmod`) no `sitemap.xml` e, se necessário, substitua o `og-image.jpg` pela arte da nova edição.
5. **Não apague** as pastas dos anos anteriores: elas mantêm o histórico do evento.

---

## 🎓 Gerador de certificados

O arquivo `certificado_palestrante_SAP.html` gera o certificado de palestrante em PDF.
As imagens dele (logos e assinatura) já estão embutidas no próprio arquivo, então ele não depende da pasta `fotos/`.
A cada edição, revise as datas e a carga horária no texto do certificado.

---

## ✍️ Contato

Dúvidas sobre o projeto: _(adicione aqui o e-mail ou contato da organização)_
