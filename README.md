## File Structure

```
apps/
 └── frontend/
        ├── public/
        └── server/
        app.vue
        nuxt.config.ts
        tsconfig.json
packages/
 ├── eslint-config-custom/
 ├── stylelint-config-custom/
 └── ui/
.env.local
.npmrc
.prettierignore
.prettierrc
docker-compose.yml
Dockerfile
package-lock.json
package.json
pnpm-lock.yaml
pnpm-workspace.yaml

turbo.json

 ```

 ## Run the app
 ```
 docker-compose up --build
 ```