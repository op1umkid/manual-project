# manual-project
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9

if __name__ == "__main__":
    temp_celsius = float(input("Введите температуру в градусах Цельсия: "))
    print(f"Температура в градусах Фаренгейта: {celsius_to_fahrenheit(temp_celsius)}")

    temp_fahrenheit = float(input("Введите температуру в градусах Фаренгейта: "))
    print(f"Температура в градусах Цельсия: {fahrenheit_to_celsius(temp_fahrenheit)}")
