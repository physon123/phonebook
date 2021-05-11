# phonebook
# python project


class Person():

    def __init__(self, name, mobile=None, office=None, email=None):

        



    def setMobile(self, number):

        



    def setOffice(self, number):

        



    def setEmail(self, address):

        

        

    def __str__(self):

        s = ''

        s += self.name + '\n'

        s += "office phone:"+self.office + '\n'

        s += "email address:"+self.email + '\n'

        return s



class PhoneBook():

    def __init__(self):        

        self.contacts = {}



    def add(self, name, mobile=None, office=None, email=None):

        

        

    def __str__(self):

        s = ''

        for p in sorted(self.contacts):

            s += str(self.contacts[p]) + '\n'

        return s



obj = PhoneBook()

obj.add("Kim", office="1234567", email="kim@company.com")

obj.add("Park", office="2345678", email="park@company.com")

print(obj)
