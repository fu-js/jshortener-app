# jshortener-app

Dự án rút gọn liên kết (URL Shortener) được xây dựng với [Next.js](https://nextjs.org) và triển khai trên [Cloudflare Workers](https://workers.cloudflare.com/).

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/fu-js/jshortener-app)

![Screenshot](screen_shot.png)

## Công nghệ sử dụng

- **Framework**: [Next.js](https://nextjs.org)
- **Runtime**: [Cloudflare Workers](https://workers.cloudflare.com/) (thông qua `@opennextjs/cloudflare`)
- **Database**: [Cloudflare D1](https://developers.cloudflare.com/d1/) với [Drizzle ORM](https://orm.drizzle.team/)
- **Authentication**: [Better Auth](https://github.com/better-auth/better-auth)
- **UI Components**: [Shadcn UI](https://ui.shadcn.com/), [Tailwind CSS](https://tailwindcss.com/), [Lucide React](https://lucide.dev/)
- **API**: [tRPC](https://trpc.io/)

## Bắt đầu

Đọc tài liệu tại https://opennext.js.org/cloudflare.

## Phát triển (Develop)

Chạy server phát triển Next.js:

```bash
npm run dev
# hoặc sử dụng package manager tương ứng
```

Mở [http://localhost:3000](http://localhost:3000) trên trình duyệt để xem kết quả.

Bạn có thể bắt đầu chỉnh sửa trang bằng cách sửa file `app/page.tsx`. Trang sẽ tự động cập nhật khi bạn chỉnh sửa file.

## Xem trước (Preview)

Xem trước ứng dụng cục bộ trên môi trường Cloudflare runtime:

```bash
npm run preview
# hoặc sử dụng package manager tương ứng
```

## Triển khai (Deploy)

Triển khai ứng dụng lên Cloudflare:

```bash
npm run deploy
# hoặc sử dụng package manager tương ứng
```

## Database

Dự án sử dụng Drizzle ORM để quản lý database.

- **Tạo migration**: `npm run db:generate`
- **Áp dụng migration (remote)**: `npm run db:push`
- **Migrate đầy đủ**: `npm run db:migrate`

## Tìm hiểu thêm

Để tìm hiểu thêm về Next.js, hãy xem các tài nguyên sau:

- [Tài liệu Next.js](https://nextjs.org/docs) - tìm hiểu về các tính năng và API của Next.js.
- [Học Next.js](https://nextjs.org/learn) - hướng dẫn tương tác về Next.js.

---

## License

MIT License

---

From JS Club with ❤️