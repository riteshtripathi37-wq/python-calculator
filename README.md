class animal:
    def eat(self):
        print("the animal is eating")
    def sleep(self):
        print("the animal is sleeping")
    def bath(self):
        print("the animal is bathing")


class rabbit(animal):
    def dance(self):
        print("the rabbit is dancing")

rabbit = rabbit()
animal = animal()
rabbit.eat()
animal.sleep()
rabbit.dance()
