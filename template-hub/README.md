## Template-Hub Usage

1. Copy `env.json.example` to `env.json` and add Notifi environment(s)
2. Create a `templates` directory and add templates   
3. Launch app: `java -jar template-hub.jar --env-file=./env.json --root-dir=./templates --server.port=9090`
4. Subscribe to the **TemplateHub** Postman team collection
5. Follow the Postman examples under the *Process* tab to push templates or global variables to a specific Notifi environment
