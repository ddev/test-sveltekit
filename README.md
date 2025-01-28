This is a test repository for DDEV automated testing of Sveltekit Node.js

* This is created with a basic starter kit of Sveltekit in this way:
  * `ddev config --webserver-type=generic --project-type=generic`
  * `ddev exec "npx sv create --template=demo --types=ts --no-add-ons . --no-add-ons --no-install"`; when it prompts " Directory not empty. Continue?", choose Yes.
  * `ddev npm install`
  * `config.extras.yaml` sets up the `web_extra_daemons` and `web_extra_exposed_ports`
  * `ddev npm run build`

