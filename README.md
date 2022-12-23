# Legit [![legit](https://github.com/RandyMcMillan/legit/actions/workflows/automate.yml/badge.svg)](https://github.com/RandyMcMillan/legit/actions/workflows/automate.yml)

##### Legit adds Proof of Work (PoW) to a git commit hash prefix.

###### As an example, take a look at a few of the commits in this repo.

### Usage:

```shell
git clone https://github.com/RandyMcMillan/legit.git
```
```shell
cd legit && make legit
```

#### add files to commit

```
git add <FILE_NAME> <FILE_NAME>
```

```
git stash (--include-untracked)
```
#### legit command
```
legit . -p "000000" -m "my legit commit"
```

```
git stash pop
```

--