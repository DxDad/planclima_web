# Protótipo PlanClima SP — versão web

Protótipo estático criado para demonstrar como o Plano de Ação Climática do Município de São Paulo — Revisão 2025 pode ser disponibilizado em formato web dentro do site do PlanClima SP.

O projeto contém duas páginas:

- `index.html`: reprodução demonstrativa da página inicial atual, com a nova opção **Plano na Web** no menu;
- `planclima-web.html`: amostra da transposição do documento, com sumário, capítulo, tabela e ficha de meta.

## Abrir localmente

É possível abrir `index.html` diretamente no navegador. Não há dependências, processo de instalação ou etapa de compilação.

## Publicar com GitHub Pages

1. Crie um repositório vazio no GitHub.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No repositório, acesse **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde a disponibilização do endereço de demonstração.

O arquivo `.nojekyll` evita processamento adicional do conteúdo pelo GitHub Pages.

## Organização dos arquivos

```text
.
├── index.html
├── planclima-web.html
├── assets
│   ├── css
│   │   └── styles.css
│   └── images
└── docs
    └── integracao-liferay.md
```

## Observações

- O protótipo não substitui o site ou o documento oficial.
- Alguns links levam para páginas e documentos do portal da Prefeitura de São Paulo.
- A transposição integral dependerá de validação editorial e técnica, especialmente para mapas, gráficos e tabelas complexas.
- O código foi construído sem frameworks e sem JavaScript obrigatório, para facilitar sua adaptação ao Liferay.

