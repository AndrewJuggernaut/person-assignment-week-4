# person-assignment-week-4
Week 4 python Assignment

class Person:
  """Represents a person with name, age, and gender."""

  def __init__(self, name, age, gender):
    """Initializes a new Person object.

    Args:
      name: The person's name.
      age: The person's age.
      gender: The person's gender.
    """
    self.name = name
    self.age = age
    self.gender = gender

  def introduce(self):
    """Prints a message introducing the person."""
    print(f"Hello, my name is {self.name}. I am {self.age} years old and I am {self.gender}.")

# Create an instance of the Person class
person = Person("Andrea", 30, "Female")

# Call the introduce method to display the person's information
person.introduce()
