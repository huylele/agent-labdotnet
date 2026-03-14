# Copilot Workspace Instructions

## Project Overview

**SocOps** là một trò chơi Social Bingo được xây dựng bằng **Blazor WebAssembly (.NET 10)**.
Người chơi di chuyển trong sự kiện thực tế, tìm những người phù hợp với các ô câu hỏi trên bảng
(ví dụ: "has a pet", "bikes to work"), đánh dấu chúng và giành chiến thắng khi hoàn thành 5 ô liên tiếp
theo hàng, cột, hoặc đường chéo.

Đây cũng là **workshop thực hành** về VS Code Agent Mode với GitHub Copilot.
Thư mục `workshop/` chứa các bước hướng dẫn từ 00 đến 05.

---

## Key Commands

```bash
dotnet build SocOps.csproj              # Kiểm tra lỗi biên dịch
dotnet run --project SocOps.csproj      # Chạy dev server → http://localhost:5166
dotnet test                                     # Chạy unit tests (khi tồn tại)
```