# XS-TK
x = (1, 'a', 2, 'b') type(x) ---> tuple # Tuples are an immutable data structure (cannot be altered). không thể thay đổi
x = [1, 'a', 2, 'b'] type(x) ---> list # Lists are a mutable data structure. có thể thay đổi
[1,2] + [3,4] ---> [1,2,3,4]

Class in python

class Person: department = 'School of Information' #a class variable

def set_name(self, new_name): #a method là 1 phương thức self.name = new_name def set_location(self, new_location): self.location = new_location

person = Person() person.set_name('Christopher Brooks') # sử dụng phương thức set_name person.set_location('Ann Arbor, MI, USA') print('{} live in {} and works in the department {}'.format(person.name, person.location, person.department)) print(person.name) # lấy ra thuộc tính name

map(function,iterable,..) # nếu iterable là mảng thì khi chạy function thì sẽ lặp từng phần tử của mảng để chạy hàm. nếu nhập vào 2 iterable thì sẽ chạy hàm function rồi đưa ra 1 trong 2 iterable dạng địa chỉ

mylist = [1, 2, 3] x = numpy.array(mylist) # chuyển my list thành mảng numpy m = numpy.array([[7, 8, 9], [10, 11, 12]]) # chuyển thành ma trận (2,3) m.shape # in ra kiểu ma trận (n,m) (rows,columns)

a = numpy.array([-4, -2, 1, 3, 5]) # sum , max , min , mean<trung bình>, std<độ chênh lệch>,argmax,argmin<chỉ số của giá trị lớn nhất và nhỏ nhất>
r = np.arange(36)

r.resize((6, 6)) ma trận 6x6 tư 0-36 # array([[ 0, 1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11], [12, 13, 14, 15, 16, 17], [18, 19, 20, 21, 22, 23], [24, 25, 26, 27, 28, 29], [30, 31, 32, 33, 34, 35]])

r[2, 2] # 14

r[3, 3:6] #array([21, 22, 23]) <hàng 3 cột 3-6>

r[:2, :-1] # array([[ 0, 1, 2, 3, 4], [ 6, 7, 8, 9, 10]]) <lấy 2 dòng từ 0:2 và lấy các cột từ 0:-1(0:5)>

r[-1, ::2] # array([30, 32, 34]) <lấy dòng cuối cùng(-1) và lấy bư nhảy là 2 (:: bước nhảy)>

r[r > 30] # array([31, 32, 33, 34, 35]) <lấy các giá trị lớn hơn 30>

r[r > 30] = 40 # gán tất cả các phần tử > 30 thành 40

r[:] = 0 # gán cả ma trận thành 0
