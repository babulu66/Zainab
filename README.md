class SimpleCalculator:
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

    def multiply(self, a, b):
        return a * b

    def divide(self, a, b):
        if b != 0:
            return a / b
        return "Cannot divide by zero"

calc = SimpleCalculator()
print(calc.add(5, 3))  # Output: 8
