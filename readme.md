## Learn about git and GitHub

> This is a file repo to learn git and GitHub basics while practicing

To push to the remote repo

```bash
git remote add origin (ssh url)
```

And to check if the remote repo has been added

```bash
git remote -v
```

To finally push the main branch

```bash
git push -u origin main
```

if `-u` is note used and just `git push origin main` is used, upstream between the local repo and remote one won't be setup and in future will have to initialize it. So if you use `-u` here, for future pushes, you only have to type

```bash
git push
```

---