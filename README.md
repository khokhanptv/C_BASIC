<details>
  <summary><h2>▶ C programming language</h2></summary> 

  <details>
  <summary><h3>Kiểu dữ liệu</h3></summary>

  ![kieu du lieu](./Pic/Kieu_Dulieu(1).PNG)
  ![kieu du lieu](./Pic/Kieu_Dulieu(2).PNG)
- Để tính kích thước của một kiểu dữ liệu trong C,  dụng toán tử sizeof.
 ```C 
#include <stdio.h>

int main() {
    int x;
    int size_of_x = sizeof(x);

    printf("Kich thuoc cua bien x la: %d byte\n", size_of_x);

    return 0;
}
 ```
  <details>
  <summary><h3>Hàm</h3></summary>

 ***Hàm có giá trị trả về***

- Sử dụng hàm có giá trị trả về khi bạn muốn hàm thực hiện một công việc cụ thể và trả về một kết quả cho phần gọi hàm. 
    - ví dụ :
```C
#include <stdio.h>

int add(int a, int b) {
    return a + b;
}
int main() {
    int x = 5;
    int y = 7;
    int sum = add(x, y);
    printf("Tong cua %d va %d la: %d\n", x, y, sum);
    return 0;
}
```
 ***Hàm void:***

- Sử dụng hàm void khi bạn muốn hàm thực hiện một tác vụ nhưng không cần trả về giá trị nào
    - ví dụ :
```C
#include <stdio.h>

void printHello() {
    printf("Hello World!\n");
}

int main() {
    printHello();
    return 0;
}
```

