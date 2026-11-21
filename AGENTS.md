# Instruções para agentes

- A aplicação fica em `code/`. Os workflows do GitHub ficam em `.github/workflows/`.
- Use o [Workflow LCR](CONTRIBUTING.md): planejamento, implementação em branch, validação, auditoria independente e aprovação do responsável antes da publicação.
- Execute `npm ci` e `npm run build` dentro de `code/`. Quando alterar assets, confira as referências com o caminho-base do GitHub Pages.
- Use WebP na visualização inicial, PNG para ampliação de evidências e SVG para marcas. Mantenha esses recursos em `code/public/assets/`.
- Versione somente documentação publicável em `documentation/public/`. Mantenha credenciais, dados reais de telemetria e registros operacionais em armazenamento autorizado.
