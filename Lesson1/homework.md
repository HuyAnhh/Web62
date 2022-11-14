Scope:
    - global: Các biến khai báo ngoài function
    - function: phạm vi bên trong function
    - block scope: - Khối bên trong dấu  {}

1. Sự khác biệt nhé giữa let, const và var
    * scope (Phạm vị)
        var -> global 
        const, let: function, block

    * assignment
        const: không thể re-assign
        let và var là có thể

    * hoisting
        var có thể sử dụng trước khi khai báo
        let, const 

2. es6
    - map => lặp qua từng phần tử của mảng => trả ra 1 mảng mới
    - filter => lặp qua mảng và trả về 1 mảng theo điều kiện lọc
    - reduce => gộp chuỗi 
    - some => nếu 1 phần tử trong mảng thỏa mãn điều kiện trả về giá trị true false
    - every => nếu tất cả phần tử trong mảng thỏa mãn điều kiện trả về giá trị true false
    - find => trả về phần tử đầu tiên được tìm thấy trong mảng thỏa mãn điều kiện
    - findIndex => trả về index của phần tử đầu tiên được tìm thấy trong mảng thỏa mãn điều kiện
    - for with index (for(let i = 0; i < nums.lentgh ; i++))
    - for in: lặp theo properties đến từng phần tử trong object
    - for of: lặp từng phần tử trong array
    - for each:  lặp riêng từng phần tử trong array

3. Spread operator (...)
4. String template (literals string)    
5. Arrow function
    - Có bao nhiêu loại function : 
        + Function 
        + Arrow Function
        + Anonymous Function
        + IIEF Function
    - Sự khác biệt giữa các loại function
    

6. Destructuring
    - Object destructuring
    - Array destructuring

7. Promise: cách tự tạo 1 cái promise, mỗi cái promise có state, cách handle promise => async/await, event-loop
8. Class 


- key : keys giúp React xác định xem những component nào đã được thay đổi, được thêm, hay bị xóa. React sẽ update lại các thay đổi này và hiển thị trên UI.

- khi dùng key bằng index. thì khi thêm xóa sửa nội dung trong chuỗi thì khi render lại react sẽ so sánh chuỗi mới do index thay đổi . các phần tử không thay đổi nội dung sẽ được cập nhật lại 