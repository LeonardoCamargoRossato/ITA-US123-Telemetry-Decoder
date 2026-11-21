# Contribuição e publicação

## Workflow LCR

1. **Planner** define o escopo, os critérios de aceite e os arquivos afetados.
2. **Builder** trabalha em uma branch ou fork, roda `npm ci` e `npm run build`, e abre um pull request com o resumo e as evidências de validação.
3. **Auditor Quality & Security** revisa o diff e os resultados da CI. Confere se a mudança preserva os links públicos da disciplina e se o PR contém somente arquivos apropriados para um repositório público.
4. **Responsável**: `@LeonardoCamargoRossato` decide e executa o merge na `main`. Em PRs de autoria do responsável, a revisão independente é registrada no PR e o merge registra a liberação.
5. **Publicação**: depois do merge, confira a execução do GitHub Actions e a página publicada. Registre no PR o resultado, sem incluir dados sensíveis.

## Dados e credenciais

Use dados simulados para demonstrações públicas. Mantenha credenciais, dados reais de telemetria, bancos locais e logs operacionais fora do Git. Use o ambiente local ou o armazenamento privado autorizado para esses arquivos.
