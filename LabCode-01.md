# LAB 01 โปรแกรมพื้นฐานภาษา C

## [ลิงค์กลับหน้าหลัก](./README.md)

## [ลิงค์เข้า LAB02](./LabCode-02.md)

## ให้นักเรียนทดลองพิมพ์ code ตามการทดลองต่อไปนี้

### การทดลองที่ 1  HelloWorld

### Code
```
#include <stdio.h>

int main()
{
    printf("Hello world!\n");
    return 0;
}
```

### การทดลองที่ 2 การประกาศตัวแปร int
### Code
```
#include <stdio.h>

int main()
{
    int apple = 3;
    int orange = 2;
    int total = apple + orange;

    printf("%d apples and %d oranges\n", apple, orange);
    printf("I have %d fruits in total", total);

    return 0;
}
```
### การทดลองที่ 3 การประกาศตัวแปร floating
### Code
```
#include <stdio.h>

int main()
{
    float pi = 3.14f;
    float half = 3 / 2.0f;
    float half2 = 3 / 2;

    printf("Pi: %f\n", pi);
    printf("Half of 3: %f\n", half);
    printf("Half of 3: %f\n", half2);
    return 0;
}
```
### การทดลองที่ 4 การประกาศตัวแปร double
### Code
```
#include <stdio.h>

int main()
{
    double gravity = 9.807;
    double earth_mass = 5.972E24;
    double meter = 1E-3;

    printf("Earth gravity: %lf m/s^2\n", gravity);
    printf("Earth mass: %lf kg\n", earth_mass);
    printf("1 centimeter: %lf meter\n" ,meter);

    return 0;
}
```
### การทดลองที่ 5 การประกาศตัวแปร boolean
### Code
```
#include <stdio.h>
#include <stdbool.h>

int main ()
{
    bool gender = 0;
    bool open = 0;

    if (gender)
    {
        printf("This is the boy.\n");
    }
    else
    {
        printf("This is the girl.\n");
    }

    if (open)
    {
        printf("The door is open.\n");
    }
    else
    {
        printf("The door is not open.\n");
    }

    return 0;
}
```
# แบบฝึกหัด
### 1.เขียนโปรแกรมแสดงชื่อ-นามสกุลตัวนักเรียน
### 2.เขียนโปรแกรมการบวกเลขของสองตัวแปร
### 3.เขียนโปรแกรมการบวกเลขของสองตัวแปรโดยผลลัพท์ต้องแสดงเป็นเลขทศนิยม

## [ลิงค์กลับหน้าหลัก](./README.md)

## [ลิงค์เข้า LAB02](./LabCode-02.md)
