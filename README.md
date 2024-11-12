
def mult(a,b):
    print(a*b)
mult(a=3, b=5)
def sloj(a,b):
    print(a+b)
sloj(a=3, b=5)
def vic(a,b):
    print(a-b)
vic(a=3, b=5)
def delen(a,b):
    print(a/b)
delen(a=3, b=5)

def umnozhenie(*chislo):
    p=1
    for cheetos in chislo:
        p*=cheetos
    return p
umnozhenie(1,2,3,4,5)

def factorial(n):
    if n == 0:
       print("1")
    else:
        result = 1
    for i in range(1, n + 1):
        result *= i
    print(result)
factorial(n=5)


numbers = [3, 7, 2, 10, 5]
def find_max(numbers):
    max_num = numbers[0]
    for num in numbers:
        if num > max_num:
            max_num = num
    return max_num
print(find_max(numbers))

ДОДЕЛАТЬ
def replace_vowels(str):
    wordle="AEIOUaeiou"
    zam_str=""
    for char in input_str:
        if char in wordle:
            zam_str = "*"
    print(zam_str)
replace_vowels("Привет, как дела?")
