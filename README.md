
## Project Introduction
This project aims to establish a comprehensive blog system, covering server-side APIs, management backends, front-end websites, and deployment. It mainly uses Node.js and the Koa2 framework for server-side API development.

### Sub-Projects
- Blog management backend (React.js + Ant Design): [react-blog-admin](https://github.com/lfb/react-blog-admin)
- Blog management backend (Vue.js + Element-UI): [vue-blog-admin](https://github.com/lfb/vue-blog-admin)
- Blog front-end display (Nuxt.js SSR): [nuxtjs-blog-web](https://github.com/lfb/nuxtjs-blog-web)

### Module Description
- **Admin Module**: Permission management, login, and registration.
- **User Module**: Login and registration on the front-end website.
- **Article Module**: Article creation, modification, deletion, and query; classification, comments.
- **Category Module**: Category management, article association.
- **Comments/Replies Module**: Management of comments and replies.

### API Documentation
For detailed API documentation, see: [Admin API](https://github.com/lfb/nodejs-koa-blog/blob/master/doc/admin.md)

## Using the Project
### Clone and Start
```
git clone https://github.com/lgb/nodejs-koa-blog.git
cd nodejs-koa-blog
npm install or yarn install
npm run dev or yarn dev
```
- Visit: `http://localhost:5000`

### Database Configuration
```
mysql -uroot -p
CREATE DATABASE IF NOT EXISTS boblog DEFAULT CHARSET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

## FAQ
1. **Yarn vs npm**: Yarn is recommended as it is faster than npm and ensures version uniformity.
2. **Startup Issues**: Ensure dependencies and databases are installed; check startup logs for errors.

## License
[MIT License](https://github.com/lfb/nodejs-koa-blog/blob/master/LICENSE)
