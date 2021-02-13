# Help Guide

## Can't resolve github Dependabot alert
**Erro:** Dependabot cannot create a pull request as one or more other dependencies require a version that is incompatible with this update.

**Solution:** Manually update all the dependencies using npm or yarn <br/>
`npm audit fix` <br/>
`yarn upgrade --latest` <br/>
