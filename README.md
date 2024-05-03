# rn-priacy-policy-aggregation-bug

![Build](https://github.com/johnf/rn-priacy-policy-aggregation-bug/workflows/Pre%20Merge%20Checks/badge.svg)

This is a reproducer for https://github.com/facebook/react-native/issues/44401

NOTE: I had to upgrade to RN0.74.1 I've just done the minimal required to get to pod update stage, so the app likely won't build.

To reporoduce simply clone and 
```sh
cd ios
pod update
```

## Reproducer todo list

- [x] Create a new reproducer project.
- [x] Git clone your repository locally.
- [x] Edit the project to reproduce the failure you're seeing.
- [x] Push your changes, so that Github Actions can run the CI.
- [x] Make sure the repository is public and share the link with the issue you reported.
