# XS-TK
x = (1, 'a', 2, 'b') type(x) ---> tuple # Tuples are an immutable data structure (cannot be altered). không thể thay đổi
x = [1, 'a', 2, 'b'] type(x) ---> list # Lists are a mutable data structure. có thể thay đổi
[1,2] + [3,4] ---> [1,2,3,4]
-----------------------------------------------------------------------------------------------------------------------------
Class in python

class Person: department = 'School of Information' #a class variable

def set_name(self, new_name): #a method là 1 phương thức self.name = new_name def set_location(self, new_location): self.location = new_location

person = Person() person.set_name('Christopher Brooks') # sử dụng phương thức set_name person.set_location('Ann Arbor, MI, USA') print('{} live in {} and works in the department {}'.format(person.name, person.location, person.department)) print(person.name) # lấy ra thuộc tính name
---------------------------------------------------------------------------------------------------------------------
map(function,iterable,..) # nếu iterable là mảng thì khi chạy function thì sẽ lặp từng phần tử của mảng để chạy hàm. nếu nhập vào 2 iterable thì sẽ chạy hàm function rồi đưa ra 1 trong 2 iterable dạng địa chỉ
-------------------------------------------------------------------------------------------------------------------------

