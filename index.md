# Help Guide

## ➜ Can't resolve github Dependabot alert

**Erro:** Dependabot cannot create a pull request as one or more other dependencies require a version that is incompatible with this update.

**Solution:** Manually update all the dependencies using npm or yarn <br/>

```bash
npm audit fix
yarn upgrade --latest
```

## ➜ ESLint error with correct code TypeScript

**Erro:** You correct the code, but the eslint still indicates an erro on your code

**Solution:** (Microsoft solution) Restart the typescript server
Ctrl + Shift + P
> TypeScript: Restart TS Server

## ➜ Checkout outdated packages and update them

```bash
yarn outdated
yarn upgrade-interactive --latest
```

## ➜ [GIT] Create new branch

```bash
git checkout -b new-branch origin/new-branch
```

## ➜ [GIT] Log as graph

```bash
git log --graph --oneline --all
  or
gitk --all
```

## ➜ [GIT] Remove file from commit history
  
```bash
git filter-repo --path [file] --invert-paths
git push --force
```

[About](./pages/about.md)
