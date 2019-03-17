print("迭代实现iteration")


def Fbnq(n):
    n1 = 1
    n2 = 1
    if n < 0:
        print("Error.")
        return -1

    while n - 2 > 0:
        n3 = n1 + n2
        n1 = n2
        n2 = n3
        n -= 1

    return n3

num = int(input("Type the num that you want:"))
result = Fbnq(num)
if result != -1:
    print(result)
