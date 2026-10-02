# OVAs educacionais

Repositório de objetos virtuais de aprendizagem para apoiar aulas, demonstrações e exploração interativa, principalmente em Física e Química.

## Projetos

### Química
- [Bancada Quiral](./quimica/bancada-quiral/) — laboratório 3D sobre enantiômeros, isomeria plana e polarimetria.

## Organização

Cada OVA fica em sua própria pasta temática, com os arquivos necessários para executá-lo e um README com objetivos, conteúdo, controles e requisitos. Assim, os projetos podem crescer de forma independente.

```text
quimica/
  bancada-quiral/
    index.html
    README.md
fisica/
  ...
```

A Bancada Quiral é executada diretamente no navegador. Ela carrega o Three.js e as fontes por CDN, então precisa de conexão com a internet.
