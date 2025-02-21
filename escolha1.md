# 1. Escolha do Markdown Architecture Records para ADRs

## Status

Aceita

## Contexto

Para documentar as decisões arquiteturais do projeto, precisamos de um formato padronizado, legível e fácil de manter no controle de versão. A escolha da ferramenta deve permitir histórico de mudanças, revisão colaborativa e integração com fluxos de desenvolvimento.

## Decisão

Optamos por utilizar Markdown Architecture Records (MADR) para as ADRs do projeto. O MADR oferece uma estrutura clara e padronizada para decisões arquiteturais, facilitando a documentação e rastreamento das escolhas feitas ao longo do desenvolvimento.

## Consequências

- **Positivas**:

  - Utiliza Markdown, que é leve, fácil de ler e editar.
  - Permite versionamento eficiente usando Git, garantindo rastreabilidade das decisões.
  - Estrutura padronizada facilita a compreensão e manutenção das ADRs.
  - Fácil integração com plataformas como GitHub, GitLab e outros repositórios de código.

- **Negativas**:

  - Exige que todos os membros da equipe estejam familiarizados com Markdown.
  - Pode demandar um pequeno esforço inicial para seguir o modelo corretamente.

# Alternativas Consideradas

- **Nygard ADR**: Um formato mais narrativo e flexível, porém menos estruturado, o que pode dificultar a padronização e comparação entre ADRs ao longo do tempo.

- **Y-Statement**: Uma abordagem focada na justificativa da decisão (por que escolhemos X em vez de Y), mas que pode não capturar detalhes estruturais tão bem quanto o MADR.