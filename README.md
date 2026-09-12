# Sobobo Confeiteira — site pronto para publicação

Landing page responsiva para a Sobobo Confeiteira, com HTML semântico, CSS externo, menu mobile acessível, SEO básico, Open Graph, dados estruturados e imagens locais.

## Estrutura

```text
sobobo-confeiteira/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    └── img/
        ├── bolo-chocolate.webp
        ├── bolo-festa-branco.webp
        ├── bombom-pistache.webp
        ├── brigadeiro-doce-leite.webp
        └── uva-chocolate-branco.webp
```

## Antes de divulgar o site

O código original não continha dados reais de contato. Por segurança, **não foram inventados telefone, endereço ou outros dados pessoais**.

Confirme/substitua no `index.html`:

1. `@soboboconfeiteira` — confirme se este é o Instagram oficial.
2. `contato@soboboconfeiteira.com.br` — confirme se o e-mail será realmente utilizado.
3. Adicione o WhatsApp real na seção de contato e no botão principal, quando o número estiver disponível.
4. Se o domínio final for diferente, ajuste os metadados de compartilhamento e, depois de publicar, acrescente a URL canônica.

## O que foi corrigido

- Corrigidos os caminhos quebrados de CSS e imagens.
- Criada a estrutura `css/` e `assets/img/` descrita no README original.
- Criado menu mobile acessível com `button`, `aria-expanded`, `aria-controls` e suporte à tecla Escape.
- Fechamento automático do menu ao clicar em um link.
- Melhorada a navegação em âncoras com `scroll-padding-top`.
- Mantido o uso de `loading="lazy"` nas imagens secundárias.
- Definida a imagem principal com `fetchpriority="high"`.
- Melhorados textos alternativos das imagens.
- Adicionados metadados SEO e Open Graph básicos.
- Adicionados dados estruturados Schema.org do tipo `Bakery`.
- Melhorados foco, contraste estrutural e navegação por teclado.
- Mantida a preferência `prefers-reduced-motion`.
- Removidos placeholders de telefone falso do link clicável.
- Mantido o site 100% estático, sem dependência de backend.

## Publicação no GitHub Pages

Envie **todo o conteúdo desta pasta** para o repositório, mantendo a estrutura de diretórios. O arquivo `index.html` deve ficar na raiz publicada.
remove: README antigo

Depois, ative GitHub Pages em **Settings → Pages** e escolha a branch/pasta usada pelo repositório.

## Observação sobre domínio e marca

A disponibilidade de um domínio e a possibilidade de registro de uma marca precisam ser confirmadas nos respectivos serviços oficiais antes de qualquer compra ou registro. Este pacote não presume que `soboboconfeiteira.com.br` esteja disponível.
