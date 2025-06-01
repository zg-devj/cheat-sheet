### Clone the Repository

```shell
git clone https://github.com/username/repository.git
```

```shell
cd repository
```

```shell
git fetch --all
```

```shell
for branch in $(git branch -r | grep -v '\->'); do
    git branch --track ${branch#origin/} $branch
done
```

```shell
git pull --all
```
