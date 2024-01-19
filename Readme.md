Run the following commands to get started:

    * cd ./gw-map-scenesapp
    * npm install to install frontend dependencies.
    * npm run dev to build (and watch) the plugin frontend code.
    * mage -v build:linux to build the plugin backend code. Rerun this command every time you edit your backend files.
    * docker-compose up to start a grafana development server. Restart this command after each time you run mage to run your new backend code.
    * Open http://localhost:3000 in your browser to create a dashboard to begin developing your plugin.

Note: We strongly recommend creating a new Git repository by running git init in ./gw-map-scenesapp before continuing.

    * Learn more about Grafana Plugin Development at https://grafana.com/developers/plugin-tools