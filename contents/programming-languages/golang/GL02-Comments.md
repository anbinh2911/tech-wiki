# Golang - Comments

## Tổng quan

Comment là các dòng text sẽ không được thực thi khi compile.

Comment có thể được dùng để giải thích code, giúp cho code dễ đọc hơn.

Comment cũng có thể dùng để đóng các dòng code lại mà không cần phải xoá đi.

Golang hỗ trợ hai loại là **single-line** và **multi-line**

## Single-line

Single-line được bắt đầu bằng (```//```). Có thể được đặt ở ngoài hàm hoặc trong hàm.

```go
package main

import "fmt"

// this is a comment
func main() {
    // this also comment
    fmt.Println("Hello")
}
```

Khi sử dụng lệnh ```go run``` thì compiler sẽ bỏ qua các dòng comment.

## Multi-line

Multi-line comment sẽ được bắt đầu bằng ```/*``` và kết thúc bằng ```*/```.

```go
package main

import "fmt"

/*
    This is multi-line comment
    Hello world
*/
func main() {
    fmt.Println("Hello")
}

```

> Thông thường sẽ sử dụng (```//```) cho các comment ngắn và (```/* */```) cho comment dài.

## Tiếp theo

- Variables & Constants.
