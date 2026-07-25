# Organização do conhecimento no CIATA

Este documento define onde cada tipo de informação deve viver no ecossistema CIATA.

## Princípio central

> **Nenhum conhecimento deve existir duplicado sem uma razão explícita.**

Links e resumos podem aparecer em vários lugares. A fonte completa e oficial deve ter um único endereço.

## Repositório `.github`

Responsável pelo nível institucional da organização:

- perfil público;
- Código de Conduta;
- política de segurança;
- orientações gerais de contribuição e suporte;
- templates compartilhados de issues e pull requests;
- identidade pública e ativos institucionais usados no GitHub.

O `.github` não deve acumular arquitetura, componentes ou guias técnicos específicos de produtos.

## Repositório `CIATA-DS`

Responsável pelos padrões reutilizáveis do ecossistema:

- identidade visual e tokens;
- design de interação;
- acessibilidade;
- linguagem e conteúdo;
- engenharia e arquitetura de referência;
- qualidade e testes;
- documentação;
- componentes e blueprints;
- práticas para colaboração humana e com agentes de inteligência artificial.

Quando um padrão puder beneficiar mais de um projeto, ele deve ser consolidado no CIATA-DS.

## Repositórios de produtos

Cada produto deve conter apenas o conhecimento necessário para compreendê-lo, executar, testar, manter e publicar.

Exemplos:

- objetivos e escopo do produto;
- arquitetura específica;
- decisões arquiteturais locais;
- configuração e instalação;
- fluxos e regras de negócio;
- procedimentos de build, teste e release;
- histórico e limitações específicas.

Padrões compartilhados devem ser referenciados, não copiados integralmente.

## Decisões

Uma decisão deve ser registrada no menor nível em que permaneça verdadeira:

- institucional: `.github`;
- transversal e reutilizável: `CIATA-DS`;
- exclusiva de um produto: repositório do produto.

## Evolução

Antes de criar um novo documento:

1. procure uma fonte já existente;
2. determine o nível correto de responsabilidade;
3. atualize a fonte oficial quando o assunto já estiver coberto;
4. prefira links a cópias;
5. registre decisões relevantes e a razão da mudança.

## Regra de saída

Todo projeto deve deixar ao menos um destes legados:

- componente reutilizável;
- padrão documentado;
- decisão registrada;
- teste reproduzível;
- aprendizado compartilhado;
- caminho mais curto para o próximo projeto.
