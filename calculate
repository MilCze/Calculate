
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y


print("Zaznacz jedną z opcji.")
print("1.Dodawanie")
print("2.Odejmowanie")
print("3.Mnożenie")
print("4.Dzielenie")

while True:
    
    choice = input("Podaj wybór: (1/2/3/4): ")

    if choice in ('1', '2', '3', '4'):
        num1 = float(input("Wprowadź pierwszą liczbę: "))
        num2 = float(input("Wprowadź drugą liczbę: "))

        if choice == '1':
            print(num1, "+", num2, "=", add(num1, num2))

        elif choice == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))

        elif choice == '3':
            print(num1, "*", num2, "=", multiply(num1, num2))

        elif choice == '4':
            print(num1, "/", num2, "=", divide(num1, num2))
        
        
        next_calculation = input("Czy chcesz wprowadzić nowe działanie? (tak/nie): ")
        if next_calculation == "nie":
          break
    
    else:
        print("Nieprawidłowe działanie")