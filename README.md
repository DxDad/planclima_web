# Protótipo PlanClima SP — versão web

Protótipo estático criado para demonstrar como o Plano de Ação Climática do Município de São Paulo — Revisão 2025 pode ser disponibilizado em formato web dentro do site do PlanClima SP.

O projeto contém duas páginas:

- `index.html`: reprodução demonstrativa da página inicial atual, com a nova opção **Plano na Web** no menu;
- `planclima-web.html`: amostra da transposição do documento, com sumário, capítulos 1 e 2 completos, linha do tempo, tabela e ficha de meta.

## Abrir localmente

É possível abrir `index.html` diretamente no navegador. Não há dependências, processo de instalação ou etapa de compilação.

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
- Esta versão apresenta integralmente os capítulos 1 e 2 e uma ficha demonstrativa do Capítulo 9.
- A transposição integral dependerá de validação editorial e técnica, especialmente para mapas, gráficos e tabelas complexas.
- O código foi construído sem frameworks e sem JavaScript obrigatório, para facilitar sua adaptação ao Liferay.
