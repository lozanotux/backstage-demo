# Backstage Demo

Demo to test Backstage

## Create Standalone Backstage

**Prerequisites:**
* Latest [Active Node.js LTS](https://nodejs.org/en/about/previous-releases)
* [yarn](https://classic.yarnpkg.com/en/docs/install)
* [Docker](https://docs.docker.com/engine/install/)
* [Git](https://github.com/git-guides/install-git)
* curl or wget

If you want to create a standalone Backstage locally on your machine, run next commands:

1. Create backstage Node.js app:

    ```bash
    npx @backstage/create-app
    ```

2. Run app:

    ```bash
    cd backstage
    ```

    ```bash
    yarn dev
    ```

## Register Components & Resources

If you want to register new components and resources from this repository, follow next steps:

1. From the web console of Backstage, navigate to **Create** → **REGISTER EXISTING COMPONENT** and use next URL: `https://github.com/lozanotux/backstage-demo/blob/main/catalog-info.yaml`

2. Click **ANALYZE** button and verify the list of components to be registered:
    ![list of components after click ANALYZE button](./media/list-of-components.png)