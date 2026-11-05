# Evidentia AI

> Evidence-based resume builder powered by retrieval-augmented generation.

## Sobre o projeto

O Evidentia AI é uma aplicação que ajuda candidatos a adaptar seus currículos para diferentes vagas utilizando informações fornecidas pelo próprio usuário.

O usuário poderá:

- escrever experiências, projetos, cursos e habilidades;
- enviar documentos profissionais;
- informar uma descrição de vaga;
- identificar competências encontradas e ausentes;
- visualizar as evidências utilizadas;
- gerar uma versão adaptada do currículo;
- revisar e editar o resultado antes da exportação.

O sistema deverá utilizar apenas informações fornecidas pelo usuário e indicar quando não encontrar evidências suficientes.

## Status

Projeto em fase inicial de planejamento.

## Objetivos

- Construir uma aplicação completa com front-end e back-end.
- Implementar um pipeline de RAG para recuperação de evidências.
- Permitir entrada manual e upload de documentos.
- Gerar currículos adaptados sem inventar experiências.
- Exibir a origem das informações utilizadas pela IA.
- Documentar experimentos realizados no Google Colab.

## Estrutura

- `backend/`: API e regras da aplicação.
- `frontend/`: interface do usuário.
- `src/evidentia/`: código reutilizável do domínio e do pipeline de IA.
- `notebooks/`: experimentos realizados no Google Colab.
- `data/sample/`: dados fictícios e anonimizados.
- `data/private/`: documentos privados, não versionados.
- `docs/`: documentação e decisões técnicas.
- `experiments/`: resultados e registros de experimentos.
- `tests/`: testes automatizados.

## Privacidade

Documentos reais de candidatos não devem ser enviados ao repositório. Use apenas dados fictícios ou anonimizados nos exemplos públicos.

## Licença

A licença será definida posteriormente.
