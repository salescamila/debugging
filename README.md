# [Help Guide](https://salescamila.github.io/help-guide/) 

Dúvidas que vou tendo ao longo do caminho

<details>
  <summary><h3>Can't resolve github Dependabot alert</h3></summary>
  
  **Erro:** Dependabot cannot create a pull request as one or more other dependencies require a version that is incompatible with this update.

  **Solution:** Manually update all the dependencies using npm or yarn <br/>
  
  ```bash
  npm audit fix
  yarn upgrade --latest
  ```
</details>

<details>
  <summary><h3>ESLint error with correct code TypeScript</h3></summary>
  
  **Erro:** You correct the code, but the eslint still indicates an erro on your code

  **Solution:** (Microsoft solution) Restart the typescript server
  Ctrl + Shift + P
  > TypeScript: Restart TS Server
</details>
<details>
  <summary><h3>Checkout outdated packages and update them</h3></summary>
  
  ```bash
  yarn outdated
  yarn upgrade-interactive --latest
  ```
</details>

<details>
  <summary><h3>[GIT] Create new branch</h3></summary>
  
  ```bash
  git checkout -b new-branch origin/new-branch
  ```
</details>

<details>
  <summary><h3>[GIT] Log as graph</h3></summary>
  
  ```bash
  git log --graph --oneline --all
    or
  gitk --all
  ```
</details>

<details>
  <summary><h3>[GIT] Remove file from commit history</h3></summary>
  
  ```bash
  git filter-repo --path [file] --invert-paths
  git push --force
  ```
</details>
