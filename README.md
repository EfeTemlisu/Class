# Class
class Dog():
  def __init__(self,name,age):
    self.name = name
    self.age = age

  def sit(self):
    print(self.name.title() + "yuvarlandı.")

  def roll_over(self):
    print(self.name.title() + "yuvarlandı")   
    
my_dog = Dog('Beyaz', 6)
print("Benim köpeğimin adı " + my_dog.name.title() + ".")
print("Benim köpeğim " + str(my_dog.age) + " yaşında.")    
