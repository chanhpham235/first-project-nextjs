1. giới thiệu
2. ssr(server side rendering) & csr(client side rendering)

- csr:
server sending response to browser
browser downloads js
browser executes react

lợi ích của client side rendering (csr):
việc rendering tài nguyên trang web sẽ nhanh hơn sau lần load đầu tiên
tăng trải nghiệm người dùng
tương thích với rất nhiều thư viện, framrwork
giúp giảm tải phía server

nhược điểm :
lần đầu load trang đầu tiên( giao diện sẽ không có ý nghĩa với user, khong có ý nghĩa với bots google )
vấn đề SEO

-ssr:
server sending ready to be rendered HTML response to browser
browser renders the page now viewable , and browser downloads js
browser executes react
page now interactable

3. cài đặt
npx create-next-app@latest nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"

yarn

