# Nội dung bài học

## Git là gì?

**Git** là một hệ thống quản lí phiên bản phân tán (Distributed Version Control System – DVCS) mã nguồn mở và miễn phí được sử dụng để quản lý hiệu quả các dự án từ nhỏ đến rất lớn.

## Repository là gì ? Cách tạo ra 1 Repository

**Repository** được hiểu là một kho lưu trữ nơi chứa các files của dự án. Các file đấy có thể là code, hình ảnh, âm thanh hoặc tất cả mọi thứ liên quan đến dự án. Bạn sẽ tổ chức kho lưu trữ của mình dưới nhiều hình thức không giống nhau, hai loại kho lưu giữ trong Github là Local Repository và Remote Repository.

### Cách tạo ra 1 Repository

**Bước 1:** Vào Github tại đây, sau đó đăng ký một tài khoản bằng việc click vào **"Sign up for Github"**.
Sau khi hoàn tất dăng nhập.Nhấn nút **"New repository"**

**Bước 2:** Nhập tên Repository và nhấn nút **“Create Repository”**. Ngoài những điều ấy ra, bạn cũng có thể thêm mô tả cho Repository (lựa chọn này không bắt buộc).

## Các trạng thái của files trong git là gì?

### File trong git có 2 trạng thái:

- **Untracked:** Là tập tin không thuộc quản lí của git

- **Tracked:** Là tập tin được đánh dấu theo dõi trong git. Trạng thái **tracked** sẽ có thêm các trạng thái khác như là **Unmodified**(chưa chỉnh sửa) , **Modified**(đã chỉnh sửa) và **Staged**(đã sẵn sàng để commit)

## Các câu lệnh trong git

- **Git clone:** Lệnh này được sử dụng để sao chép một kho lưu trữ (repository) từ một kho chứa từ xa (remote repository) vào máy tính.

- **Git push:** Lệnh này được sử dụng để đẩy các file đã được commit ở local lên remote.

- **Git pull:** Lệnh này được sử dụng để kéo các file trên remote về local sau đó sẽ merge với nhánh hiện tại.

- **Git fetch:** Lệnh này được sử dụng để kéo cái file trên remote về local nhưng không merge với branch ở local.

- **Git merge:** Lệnh này được sử dụng để hợp nhất các nhánh khác nhau lại với nhau.

- **Git add:** Lệnh này được sử dụng chuyển các file vào trạng thái staged(sẵn sàn để commit).

- **Git commit:** Lệnh này được sử dụng để lưu trạng thái hiện tại của các tệp đã được đánh dấu (staged) trong một lịch sử phiên bản.

- **Git reset:** Lệnh này được sử dụng để chuyển các file đã được đánh dấu về lại trạng thái đang làm việc.

- **Git reset --soft:** Lệnh này được sử dụng để xoá commit nhưng các file trong commit sẽ chuyển sang trạng thái staged.

- **Git reset --mixed:** Lệnh này được sử dụng để xoá commit nhưng các file trong commit sẽ chuyển về trạng thái chưa được đánh dấu.

- **Git reset --hard:** Lệnh này được sử dụng để xoá commit đồng thời các file trong commit sẽ xoá luôn.

- **Git cherry-pick:** Lệnh này được sử dụng để lấy các commit của nhánh khác về nhánh hiện tại.

- **Git stash save:** Lệnh này được sử dụng để chuyển các file (ngoại trừ file ở trạng thái untracked) chưa được commit vào một kho lưu trữ tạm.

- **Git stash save -u:** Lệnh này được sử dụng để chuyển các file (kể cả file ở trạng thái untracked) chưa được commit vào một kho lưu trữ tạm.

- **Git stash list:** Lệnh này được sử dụng để kiểm tra danh sách các kho lưu trữ tạm.

- **Git stash apply:** Lệnh này được sử dụng chuyển phân rã một kho lưu trữ tạm nhưng kho đó sẽ không bị xoá.

- **Git stash pop:** Lệnh này được sử dụng chuyển phân rã một kho lưu trữ tạm đồng thời kho đó cũng sẽ bị xoá.
