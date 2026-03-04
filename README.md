# Backend Mentoring

Repo tự ôn kiến thức backend — đi từ nền tảng đến thực chiến.

## Mục tiêu

- Nắm vững kiến thức backend cốt lõi (HTTP, REST, database, auth, ...)
- Tư duy thiết kế API đúng chuẩn, biết giải thích được "vì sao"
- Thực hành qua bài tập thiết kế và code thực tế mỗi ngày

## Cấu trúc

Mỗi buổi học là một folder `dayXXX/`, bên trong gồm:


| File        | Mô tả                                     |
| ----------- | ----------------------------------------- |
| `dayXXX.md` | Đề bài: câu hỏi kiến thức + task thiết kế |
| `mentee.md` | Template để mentee nộp bài                |


## Cách học

1. Đọc `dayXXX.md` — hiểu đề bài và yêu cầu
2. Tự research và trả lời vào `mentee.md`
3. Review cùng mentor hoặc AI, nhận feedback

### Muốn submit để mọi người cùng review?

1. **Fork** repo này về GitHub cá nhân
2. **Clone** repo đã fork về máy
3. Tạo branch mới theo format: `dayXXX/<github-username>`
4. Làm bài trong `mentee.md`
5. Commit, push lên fork
6. Tạo **Pull Request** về repo gốc

```bash
# Ví dụ cho Day001 (GitHub username: johndoe)
git checkout -b day001/johndoe
# ... làm bài trong day001/mentee.md ...
git add .
git commit -m "day001: answer questions and design API"
git push origin day001/johndoe
# → Tạo Pull Request trên GitHub
```

## Author

**lppduy**

- GitHub: [github.com/lppduy](https://github.com/lppduy)
- Email: [lppduy@gmail.com](mailto:lppduy@gmail.com)
- LinkedIn: [linkedin.com/in/lppduy](https://www.linkedin.com/in/lppduy/)

## Lộ trình

| Day | Chủ đề | Đề bài |
| --- | ------ | ------ |
| 001 | HTTP & REST Foundation | [day001.md](day001/day001.md) |
| ... | *(đang cập nhật)* | |

