# Help Guide


## ➜ Can't resolve github Dependabot alert
**Error:** Dependabot cannot create a pull request as one or more other dependencies require a version that is incompatible with this update.

**Solution:** Manually update all the dependencies using npm or yarn <br/>
```bash
npm audit fix
yarn upgrade --latest
```
<br/>

<hr>
[About](./pages/about.md)
