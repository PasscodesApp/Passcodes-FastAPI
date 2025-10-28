# Installation

There are multiple ways for installation & running the server.

- Pythonic Standard Way. (Best For Developers & Tech Users)
- Standalone Executable Way. (Very Easy For Non Tech User)
- Docker's Way. (Best Homelabs)
- Github Forking Way. (Best For Developers Who Want To Extend)

## Pythonic Standard Way

**Best For**: 
- Developer & Software Engineers.
- Best for those, how has knowledge of git & github.
- It's the git standard way.
- It easy to update the backend to latest versions.

**Prerequisites**: `UV (package manager)` & `Git`.

- Ensure you have Git & UV install.

  ```bash
  uv --version
  git --version
  ```

- Clone the Repository.

  ```bash
  git clone https://github.com/PasscodesApp/Passcodes-FastAPI.git
  ```

- Download Dependency.

  ```bash
  uv sync
  ```

- Run Server (Production).

  ```bash
  fastapi run app/main.py --port 8080
  ```

> [!NOTE]
> Then, you can update to latest just by git pull,
> or you can even revert to previous version. if, bug is found.

## Standalone Way (Pychrubile Way)

> [!NOTE]
> We will try if possible (using scripts) to provide a single command that you can run in terminal.
> that work on every platform, and can directly run the server for you.

**Best For**: 
- Non tech user.
- Simple & easy for test & expirement.
- Little bit complicated to update i guess.

**Prerequisites**: `Zero Prerequisites`.

1) Download the executable form the GitHub Release page.
2) Ignore the warning from the windows defender or antivirus provider.
3) If required give execution permission to the executable (linux only)
4) Run executable.

> [!TODO] Write the step for how download and run the executable.

## DockerFile

**Best For**: 
- Software Engineers & Homelab user.
- Reliability.

**Prerequisites**: `Docker Desktop` & `Git`.

1) Download the container image from github registry.

2) run the container image.

> [!TODO] write the specific steps for how download container image and run it.

## Github Forking Way

**Best For**: 
- Whose how wanna use and extend the functionality.
- It's the github standard way.
- It easy to update the backend to latest versions.

**Prerequisites**: `Git` & `UV (Package Manager)`.

This just like above pythonic way, but just be sure to fork the repository. 
Then use you own fork repository.
