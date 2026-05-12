 Class: is like blueprint or template for creating object. It defines properties (data) and behaviors(action)that object will have
 Object is a specific instance of class. It contain data and behavior defined in the class.

         example1: showing the car, brand,model and price.

         class phone:
    def __init__(self, brand, model, price):
        self.brand=brand
        self.model=model
        self.price=price
    def display_info(self): 
        print("phone brand",self.brand)
        print("model",self.model)
        print("price",self.price)
phone1=phone("sumsang", "galaxy A15", 7000000) 
phone2=phone("iphone","iphone13", 1000000)

phone1.display_info()
phone2.display_info()

OUTPUT:
phone brand sumsang
model galaxy A15
price 7000000
phone brand iphone
model iphone13
price 1000000

        example2🧑‍🎓student details, including, name, age, course, school, email.

        class student:
        

    def __init__(self, name, age, course, school, email):
        self.name = name
        self.age = age
        self.course = course
        self.school = school
        self.email = email

    def display_info(self):
        print("student name:", self.name)
        print("age:", self.age)
        print("course:", self.course)
        print("school",self.school)
        print("email", self.email)

student1 = Student("alice", 20, "python","east afric community", "alice@gmail.com")
student2 = Student("john", 22, "networking", "UR","john@gmail.com")

student1.display_info()
student2.display_info()
OUTPUT:

student name: alice
age: 20
course: python
school east afric community
email alice@gmail.com
student name: john
age: 22
course: networking
school UR
email john@gmail.com









