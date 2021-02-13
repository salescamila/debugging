# Help Guide / Guia de Ajuda

Dúvidas que vou tendo ao longo do caminho

## Can't resolve github Dependabot alert
**Erro:** Dependabot cannot create a pull request as one or more other dependencies require a version that is incompatible with this update.

**Solution:** Manually update all the dependencies using npm ( `npm audit fix` ) or yarn ( `yarn upgrade --latest` )