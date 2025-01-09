<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chọn Món Ăn</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 20px;
        padding: 0;
      }
      h1 {
        text-align: center;
      }
      form {
        margin-bottom: 20px;
      }
      input[type="text"] {
        padding: 8px;
        width: 300px;
        margin-right: 10px;
      }
      input[type="submit"] {
        padding: 8px 15px;
        cursor: pointer;
      }
      .list {
        margin-top: 20px;
      }
    </style>
  </head>
  <body>
    <h1>Chọn Món Ăn</h1>
    <form id="foodForm">
      <input type="text" id="name" placeholder="Nhập tên của bạn" required />
      <input
        type="text"
        id="food"
        placeholder="Nhập món ăn bạn chọn"
        required
      />
      <input type="submit" value="Gửi" />
    </form>

    <div class="list">
      <h2>Danh sách món ăn đã chọn:</h2>
      <ul id="foodList"></ul>
    </div>

    <script>
      // Lấy dữ liệu từ localStorage
      function getFoodData() {
        const data = localStorage.getItem("foodData");
        return data ? JSON.parse(data) : [];
      }

      // Hiển thị danh sách món ăn
      function renderFoodList() {
        const foodList = document.getElementById("foodList");
        foodList.innerHTML = ""; // Xóa danh sách cũ
        const data = getFoodData();
        data.forEach((item) => {
          const li = document.createElement("li");
          li.textContent = `${item.name}: ${item.food}`;
          foodList.appendChild(li);
        });
      }

      // Xử lý khi người dùng gửi form
      document
        .getElementById("foodForm")
        .addEventListener("submit", function (e) {
          e.preventDefault();
          const name = document.getElementById("name").value.trim();
          const food = document.getElementById("food").value.trim();

          if (name && food) {
            const data = getFoodData();
            data.push({ name, food }); // Thêm dữ liệu mới
            localStorage.setItem("foodData", JSON.stringify(data)); // Lưu vào localStorage
            renderFoodList(); // Cập nhật danh sách hiển thị
            this.reset(); // Xóa dữ liệu trong form
          }
        });

      // Hiển thị danh sách khi tải trang
      renderFoodList();
    </script>
  </body>
</html>
