# CD LTD. Authorized Use Only

This toolchain deploys the [DESC] project.

Microservices:
* [insurance-desc][desc_github_url] - An API to retrieve and update a catalog of insurance policies
* [insurance-orders][orders_github_url] - An API to retrieve and update a list of insurance policy orders made by customers
* [insurance-bot][bot_github_url] - UI that provides a chat bot interface for users to query their health benefits and file claims.
* [insurance-bot-dashboard][dashboard_github_url] - A user interface showing an history of the bot chats for further analysis.
* [insurance-bot-ios][ios_github_url] - An iOS application for the chat bot.
* [insurance-bot-android][android_github_url] - An Android application for the chat bot.

## Create the toolchain

1. Ensure you have 2GB of free memory and space for 5 additional services in your organization.

1. It is recommended to create a new space in your organization. This helps grouping the apps and services together in the console.

1. **Auto-Deploy button:**

  [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://new-console.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com//https://github.com/wickedpaper/demotoolchain)

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

