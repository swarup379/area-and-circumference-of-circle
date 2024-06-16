class circle:
    pi=3.14159
    def __init__(self,radius):
        self.radius=radius
    def area(self):
        return (circle.pi)*(self.radius)*(self.radius)
    def circum(self):
        return 2*(self.radius)*(circle.pi)
c=circle(6)
print(c.area())
print(c.circum())
