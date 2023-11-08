 # Repository Duplication Guide

This guide explains how to duplicate a GitHub repository, without losing your git commit

## Duplicating a Standard Repository

1. **Open Git Bash.**

2. **Create a bare clone of the original repository.**

   ```shell
   git clone --bare https://github.com/EXAMPLE-USER/OLD-REPOSITORY.git

### Duplicate-push to the new repository.

```
cd OLD-REPOSITORY.git
```
### Create a new repository where you can duplicate this repository
```
git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
```
### Remove the temporary local repository you created earlier.

```
cd ..
rm -rf OLD-REPOSITORY.git
```