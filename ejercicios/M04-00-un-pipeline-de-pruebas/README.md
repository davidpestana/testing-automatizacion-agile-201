# M04-00 — Un pipeline de pruebas

Ejercicio de la demostración [Un pipeline de pruebas](../../labs/M04-ci-cd-testing-continuo/00-un-pipeline-de-pruebas.md):
una función `totalCarrito` con tres pruebas de Vitest y el workflow `demo-pipeline.yml` que las ejecuta en GitHub Actions.

```bash
# Ejecuta las pruebas en tu terminal (lo mismo que hace el workflow)
cd ejercicios/M04-00-un-pipeline-de-pruebas
npx vitest run --reporter=verbose
```

Para verlo en Actions, copia el workflow a la carpeta de workflows de la raíz del repositorio:

```bash
# Desde la raíz del repositorio
mkdir -p .github/workflows
cp ejercicios/M04-00-un-pipeline-de-pruebas/demo-pipeline.yml .github/workflows/
```


