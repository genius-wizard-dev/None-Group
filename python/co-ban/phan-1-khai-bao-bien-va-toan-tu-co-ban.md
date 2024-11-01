---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Phần 1: Khai Báo Biến và Toán Tử Cơ Bản

Python là một ngôn ngữ lập trình dễ học và sử dụng. Trong phần này, chúng ta sẽ tìm hiểu cách khai báo biến, các kiểu dữ liệu và các toán tử cơ bản trong Python.

### 1. Khai báo Biến

Khi bạn muốn lưu trữ một giá trị nào đó, bạn có thể sử dụng biến. Ví dụ:

```python
x = 5  # Lưu trữ số nguyên 5 vào biến x
name = "John"  # Lưu trữ chuỗi "John" vào biến name
is_valid = True  # Lưu trữ giá trị đúng (True) vào biến is_valid
```

#### Gán Kiểu Dữ Liệu

Trong Python, bạn không cần chỉ định kiểu dữ liệu khi khai báo biến như Java, C, C++,... Tuy nhiên, bạn có thể làm điều đó bằng cách sử dụng chú thích kiểu (type hint).&#x20;

```python
a: int = 3  # a được chỉ định là kiểu số nguyên
```

Chú ý rằng nếu bạn cố gắng gán giá trị không đúng kiểu, như sau:

```python
a: int = "Hello"  # Lỗi: Giá trị không phải là số nguyên
```

Python sẽ vẫn chạy đoạn mã trên mà không báo lỗi chỉ khi bạn sửa dụng công cụ kiểm tra dữ liệu thì lỗi mới được thông báo.

### 2. Các Kiểu Dữ Liệu Cơ Bản

Python hỗ trợ nhiều kiểu dữ liệu khác nhau:

*   **Số nguyên (int)**: Số nguyên không có phần thập phân. Ví dụ:

    ```python
    a = 5
    ```
*   **Số thực (float)**: Số có phần thập phân. Ví dụ:

    ```python
    b = 5.5
    ```
*   **Chuỗi (str)**: Dãy ký tự. Ví dụ:

    ```python
    name = "Alice"
    ```
*   **Giá trị đúng/sai (bool)**: Giá trị đúng (`True`) hoặc sai (`False`). Ví dụ:

    ```python
    is_valid = True
    ```
*   **Danh sách (list)**: Danh sách các giá trị có thể thay đổi. Ví dụ:

    ```python
    numbers = [1, 2, 3]
    ```
*   **Tuple**: Giống danh sách nhưng không thể thay đổi. Ví dụ:

    ```python
    coordinates = (10, 20)
    ```
*   **Từ điển (dict)**: Bộ dữ liệu lưu trữ các cặp khóa-giá trị. Ví dụ:

    ```python
    student = {"name": "Alice", "age": 20}
    ```
*   **Tập hợp (set)**: Tập hợp các giá trị duy nhất. Ví dụ:

    ```python
    unique_numbers = {1, 2, 3, 3}  # Kết quả: {1, 2, 3}
    ```

### 3. Toán Tử Cơ Bản

#### 3.1 Toán Tử Số Học

Dưới đây là các toán tử số học cơ bản trong Python:

*   **Cộng (+)**:

    ```python
    result = 5 + 3  # Kết quả: 8
    ```
*   **Trừ (-)**:

    ```python
    result = 10 - 4  # Kết quả: 6
    ```
*   **Nhân (\*)**:

    ```python
    result = 6 * 2  # Kết quả: 12
    ```
*   **Chia (/)**:

    ```python
    result = 15 / 3  # Kết quả: 5.0
    ```
*   **Chia lấy phần nguyên (//)**:

    ```python
    result = 17 // 3  # Kết quả: 5
    ```
*   **Chia lấy phần dư (%)**:

    ```python
    result = 17 % 3  # Kết quả: 2
    ```
*   **Lũy thừa (**)\*\*:

    ```python
    result = 2 ** 3  # Kết quả: 8
    ```

#### 3.2 Toán Tử Gán Kết Hợp

Bạn có thể gán giá trị và thực hiện phép toán cùng một lúc:

*   **Cộng và gán (+=)**:

    ```python
    x = 5
    x += 3  # Tương đương với x = x + 3, Kết quả: x = 8
    ```
*   **Trừ và gán (-=)**:

    ```python
    x -= 2  # Tương đương với x = x - 2, Kết quả: x = 6
    ```
*   **Nhân và gán (\*=)**:

    ```python
    x *= 2  # Tương đương với x = x * 2, Kết quả: x = 12
    ```
*   **Chia và gán (/=)**:

    ```python
    x /= 4  # Tương đương với x = x / 4, Kết quả: x = 3.0
    ```

#### 3.3 Cộng Danh Sách với Danh Sách

Khi bạn cộng hai danh sách, bạn sẽ có một danh sách mới:

```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined = list1 + list2  # Kết quả: [1, 2, 3, 4, 5, 6]
```

***

Hy vọng tài liệu này giúp bạn nắm vững các khái niệm cơ bản về khai báo biến và toán tử trong Python. Nếu bạn có bất kỳ câu hỏi nào hoặc cần thêm thông tin, hãy cho tôi biết!
