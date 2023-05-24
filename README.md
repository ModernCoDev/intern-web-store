# intern-web-store
Welcome to the Study Fullstack Shop Project, an exciting opportunity for interns to gain hands-on experience in developing a comprehensive e-commerce application using cutting-edge technologies. This repository serves as a central hub for all resources, documentation, and code related to the project.

This project enforces the use of pull requests for every code push, promoting collaborative code review, ensuring high-quality contributions, and fostering effective teamwork. By requiring pull requests, it streamlines the code integration process and enhances transparency and accountability in version control.

# Git Workflow:

1. Create new branch from main:

```Shell
git checkout main
```

```Shell
git branch -b new-branch
```
2. Make changes to the codebase then stage and commit

```Shell
git add .
```

```Shell
git commit -m "Your commit message"
```
3. Push the changes to the remote repository:

```Shell
git push origin new-branch
```

4. Visit the repository on GitHub and navigate to the branch you just pushed.
5. Click on the "New pull request" button.
6. Review the changes in the pull request, provide any necessary context, and select the appropriate reviewers.
7. Click on the "Create pull request" button to submit the pull request.

# Monorepo

A monorepo is a software development approach where multiple projects or components are stored in a single repository. It promotes code sharing, simplifies dependency management, and streamlines collaboration among developers. By centralizing code and assets, it enables easier code reuse, atomic commits, and streamlined build and deployment processes.

This project uses [NX](https://nx.dev/getting-started/why-nx) to simplify and make it more efficient to work on monorepo.

# Microfrontends

Microfrontends is an architectural pattern where a frontend application is composed of loosely coupled, independently deployable, and individually developed components. Each component represents a small, self-contained frontend application that can be developed, tested, and deployed independently. This approach allows teams to work autonomously, enables technology flexibility, and facilitates scaling and maintenance of complex frontend systems.
