<p align="center">
  <img src="https://github.com/bootgly/.github/raw/main/favicon-temp1-128.png" alt="bootgly-logo" width="120px" height="120px"/>
</p>
<h1 align="center">Bootgly.Console template</h1>
<p align="center">
  <i>Bootgly Console Workables template</i>
</p>
<p align="center">
  <a href="https://packagist.org/packages/bootgly/bootgly">
    <img alt="Bootgly License" src="https://img.shields.io/github/license/bootgly/bootgly"/>
  </a>
</p>

You should use this repository to start building your CLI workables.

This repository serves as a template (starter kit) for creating CLI applications using the Bootgly CLI, which is a part of the [Bootgly PHP Framework][BOOTGLY_PHP_FRAMEWORK].

## 🧩 Templating

### 1️⃣ Using Git

#### Git init from template

To get started with the Bootgly Console template repository on GitHub, follow the steps below:

1. Navigate to the main page of the Bootgly Console template repository on GitHub.
2. Click on the "Use this template" button located near the top-right corner of the repository page:
![Click on the "Use this template"](https://github.com/bootgly/.github/raw/main/screenshots/bootgly-php-framework/Bootgly.CLI-template.png)
3. On the "Create a new repository" page, provide a name for your new repository.
4. Optionally, add a description and choose the visibility and permissions for your repository.
5. Click on the "Create repository from template" button to create your new repository based on the Bootgly Console template.
6. Clone your repository created from the template.

#### Initialize and update Submodules

> Git submodules are a useful feature that allows you to include one Git repository inside another. In the context of your Bootgly Console template, we can use submodules to include any bootable repository (`bootgly-*`) in your project. This tutorial will guide you through the process of using Git submodules in your Bootgly Console template project.

1. Open your terminal or command prompt.
2. Navigate to your cloned Bootgly Console template project directory.
3. To init the submodules, use the following commands:

```
git submodule update --init --recursive
```

### 2️⃣ Using Composer

If you prefer using Composer to manage your PHP dependencies, follow the steps below to initialize the Bootgly Console template repository:

<details>
  <summary><b>Option 1: create-project command</b></summary>

  To create a new project using the Bootgly Console template and Composer's create-project command, follow these steps:

  1. Open your terminal or command prompt.
  2. Run the following command to create a new project based on the Bootgly Console template:

  ```
  composer create-project bootgly/bootgly.console bootgly.console
  ```

  Replace `bootgly.console` with the desired name of your project directory.

  **Composer will download the Bootgly Console template and its dependencies, and create the project structure for you.**
</details>

<!--
#### Option 2 - package init

1. Open your terminal or command prompt.
2. Create a new directory for your project and navigate to it:

```
mkdir my-bootgly-console-app
cd my-bootgly-console-app
```

3. Initialize a new Composer project within your directory:

```
composer init
```

4. When prompted, provide the necessary information for your project such as package name, description, author, etc.
5. After completing the initialization, open the composer.json file in a text editor.
6. Under the require section, add the following line to include the Bootgly CLI template as a dependency:

```json
"require": {
   "bootgly/bootgly.console": "1.0.0"
}
```

7. Save the changes to the composer.json file.
8. Run the following command to install the Bootgly Console template and its dependencies:

```
composer install
```
-->
## 🔜 Next Steps

Once you have initialized your Bootgly Console template repository either using GitHub or Composer, you can start developing your CLI application. Here are a few recommended steps to get started:

1. Review the [Bootgly documentation][BOOTGLY_DOCS] to understand the features and capabilities of the Bootgly CLI.
2. Check `projects\*.constructor.php` files. Add new commands, instance CLI components, and update the application configuration as needed.
3. Test your Console application locally to ensure it functions as expected. You can use the provided testing tools and utilities included in the Bootgly CLI.
4. Add any additional dependencies or libraries your application requires to the composer.json file and install them using Composer.
5. Document your CLI application by updating the README file and providing instructions on how to use and configure your application.
6. Once you are ready, consider publishing your CLI application to Packagist to make it available to others. Follow the Packagist documentation for guidelines on publishing your project.

That's it! You now have a solid foundation for building your CLI application using the Bootgly CLI. Happy coding!

## 📃 License

The Bootgly PHP Framework is open-sourced software licensed under the [MIT license][MIT_LICENSE].

<!-- Links -->
[BOOTGLY_DOCS]: https://docs.bootgly.com
[BOOTGLY_PHP_FRAMEWORK]: https://github.com/bootgly/bootgly
[MIT_LICENSE]: https://opensource.org/licenses/MIT
