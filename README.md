# Rust Development Template

This Rust template is meant to help you get quickly started with a new project. It is [Codespaces enabled](https://docs.github.com/en/codespaces/overview) and it is pre-configured with useful extensions like the [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer&WT.mc_id=academic-0000-alfredodeza) and [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode).

It's based on the [template created by Alfredo Deza](https://github.com/new?template_name=rust-template&template_owner=alfredodeza). The main difference is my version doesn't use [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot). Instead, it installs [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode), the Microsoft's AI coding assistant. But IntellliCode is much more limited in comparison. 

If you find a good free alternative to Copilot that supports Rust development well and it's also Devcontainer-friendly, please let me know. Here are the options I've tried so far, but I had to install their VS Code Extensions manually:

- [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) - AI code completion tool that supports Rust.

- [Cody AI](https://marketplace.visualstudio.com/items?itemName=cody.cody) - AI pair programmer extension by Anthropic.

- [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium) - AI coding assistant for multiple languages including Rust.


## Getting Started

To get started with this template, start by  [generating the repository](https://github.com/new?template_name=rust-template&template_owner=msugar).

Then, clone the repository and run the following `cargo` command (replace `my-project` with the name of your own project) inside it:

```bash
cargo init --name my-project .
```

This will initialize the project with the name you provided. You can now start editing the `src/main.rs` file and building your project.

## Make changes

Make changes to this repository so that it reflects your own project. Start by updating the license which is currently set to MIT. You can do this by editing the `LICENSE` file. You can also update the `README.md` file to reflect a descriptiton of your own project.

## GitHub Actions

This template comes with a GitHub Actions workflow that will run on every push to the repository. The workflow will run `cargo build` and `cargo test` to make sure that your project builds and that all tests pass. You can find the workflow file in `.github/workflows/rust.yml`

## GitHub Codespaces

This template is [Codespaces enabled](https://docs.github.com/en/codespaces/overview). This means that you can start a new Codespace from this repository and start working on your project right away. To do this, click on the green "Code" button and select "Open with Codespaces". This will start a new Codespace for you and you can start editing the files right away.

## Resources

This template repository is part of a 4-week Rust course, [start on week 1 here](https://github.com/alfredodeza/rust-setup) if you want to learn more about Rust!

**Coursera Course**

- [Rust Fundamentals](https://www.coursera.org/learn/rust-fundamentals)

**O'Reilly Course**

- [Rust Bootcamp](https://s.deza.pe/zjo)


