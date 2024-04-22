1. Create Vercel postresql db
2. mkdir project-folder && cd project-folder
2. npx create-medusa-app@latest --db-url "postgres://default:passwordhost-region.postgres.vercel-storage.com:5432/verceldb?sslmode=require"
3. npm install @medusajs/medusa-cli -g 
4. cd my-medusa-store
5. npx medusa user -e some@email.com -p somepassword //create admin user
6. medusa develop (launches admin)
7. login to admin
7. cd <project-folder>/my-medusa-store-storefront && yarn dev //opens storefront at localhost:8000
