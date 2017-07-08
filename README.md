
1. **Auto-Deploy button:**

  [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://new-console.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/wickedpaper/demotoolchain.git)

  Clicking it will:
  * **create 4 GitHub repositories** with the required source code for all the application components;
  * **instantiate the toolchain** in Bluemix org and space;
  * **trigger the toolchain**, thereby deploying the selected branches (default to master) for all application components.


The toolchain is preconfigured for:

- issue tracking
- source control
- continuous delivery and integration (CI/CD)
- unit and code coverage testing
- blue-green deployment

