 # How to Duplicate a GitHub Repository Without Losing Git Commits

 Learn to duplicate GitHub repositories without losing commits. Safely back up, collaborate, and explore projects with this step-by-step guide.





## Duplicating a Standard Repository

1. **Open Git Bash.**

2. **Create a bare clone of the original repository.**

 ```
 git clone --bare https://github.com/EXAMPLE-USER/OLD-REPOSITORY.git
```
```
cd OLD-REPOSITORY.git
```

### Create a new repository where you can duplicate this repository

```
git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
```
## Thank you
