# Create a new project

ModExpedite provides a CLI tool that helps you set up a new project with a single command.

## Prerequisites:

- This project runs with Bun, so the only thing needed here is to have [Bun installed.](https://bun.sh/docs/installation)

## Create project:

To create a new project, run the following command from the terminal:

```bash
bunx modexpedite
```

You will then be asked for some information about your project:

### Company and project name:

These are used to generate the namespace that will be used on your project files.

- **Company Name**: A short version of your company or studio name. For example, if your company is called "One Example Studios", you could use "oestudios". You can also use your own name or nickname if you don't have a studio.

- **Project Name**: A short version of your project name. For example, if your project is called "My Awesome Add-On", you could use "my_awesome_addon".

### Destination paths:

These are the paths where your project will be generated. If you are on Windows, the framework will automatically detect the com.mojang folder and create the project there. If you are on Linux or MacOS, you will need to provide the path to save the generated Behavior and Resource files.
