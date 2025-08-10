# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

```
yarn strapi deploy
```

# CMS Admin (Strapi Backend)

Backend CMS cho website/blog đa chủ đề.  
Tech stack: **Strapi 4 (Node.js)**, **SQLite** (local), **PostgreSQL** (production), **REST/GraphQL API**.

## 🎯 Mục tiêu
- Quản lý toàn bộ nội dung bài viết, danh mục, tag.
- Hỗ trợ soạn thảo bài với trình editor, upload ảnh.
- Phân quyền (Admin/Editor/Author) rõ ràng.
- Cung cấp API (REST & GraphQL) cho frontend (`web-user`).

## 🚀 Công nghệ chính
- **Strapi 4** – CMS headless, dễ tuỳ biến.
- **Node.js 20** – môi trường runtime.
- **SQLite** – database cho local dev (nhanh, gọn).
- **PostgreSQL** – database cho môi trường production.
- **Supabase Storage/Cloudinary** – lưu trữ ảnh.

## 🛠 Cách chạy local
```bash
npm install
npm run develop
# Mở http://localhost:1337 (trang admin ở /admin)

Biến môi trường (.env)
APP_KEYS=changeme1,changeme2,changeme3,changeme4
API_TOKEN_SALT=changeme
ADMIN_JWT_SECRET=changeme
JWT_SECRET=changeme

Lộ trình phát triển
W0: Khởi động & chuẩn bị (đang thực hiện)
W1: Tạo Content Types (Post, Category, Tag), mở public API, cấu hình CORS
W2: Tích hợp với web-user, kiểm thử CRUD bài viết
W3: Tối ưu query, phân quyền nâng cao
W4: Deploy production + backup & monitoring

Cấu trúc thư mục chính
config/          # Cấu hình server, middleware, plugin
database/        # Migrations và seeds
src/
  api/           # Content Types & Controllers
  extensions/    # Tuỳ chỉnh plugin
public/uploads/  # Ảnh upload local (nên ignore trong Git)


## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
