## CMake vcpkg vscode remote container example project

## Dependencies
VSCode, Docker,Docker compose, and the Remote-Containers plugin


## Steps to build and run
1. Bring up containers `docker-compose up -d`
2. Reopen in container `f1 Remote-container: Reopen in Container`
3. From the command palette in VS Code, run the `CMake: Configure` command.
4. From the command palette in VS Code, run the CMake: Build command
5. run with `./build/main` or use the debugger