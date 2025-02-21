# 6. Escolha de usar API da OpenAI

## Status

Aceita

## Contexto

O projeto precisa de um sistema de recomendação de treinos baseado em IA. Para isso, decidimos integrar com um modelo de IA pré-treinado para gerar sugestões personalizadas de treino para os usuários.

## Decisão

Optamos por usar a **API da OpenAI**, que oferece acesso a modelos de linguagem poderosos como o GPT, principalmente pela sua fácil integração com Python.

## Consequências

- **Positivas**:
  - Fácil de integrar e utilizar modelos de IA avançados sem a necessidade de treinar modelos do zero.
  - Oferece suporte e documentação para integração com APIs.
  
- **Negativas**:
  - Ao contrário de outras APIs que consideramos, a da OpenAI não é gratuita, então a equipe precisou se juntar para comprar os Tokens necessários para desenvolver o projeto.

## Alternativas Consideradas

- **Gemini**: Apesar de gratuita, a API do Gemini é mais difícil de integrar com Python do que a da OpenAI.