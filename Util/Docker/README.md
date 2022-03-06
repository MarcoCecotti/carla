# Building Carla in a Docker
```
docker build --build-arg EPIC_USER=<GitHubUserName> --build-arg EPIC_PASS=<GitHubPassword> -t carla-prerequisites -f Prerequisites.Dockerfile .
```
```
docker build -t carla -f Carla.Dockerfile .
```

# Launching Carla
Run the following command in the carla folder, it compiles and launches Unreal Engine:
```
make launch
```

# Adjusting mouse sensitivity in UE4
Set the value to 0.005 under Editor Preference -> Level Editor -> Viewports -> Mouse Sensitivity.
