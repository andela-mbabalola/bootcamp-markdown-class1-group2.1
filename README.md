
##A function that checks if a number is prime or not
def isPrime(number):
	num = int(input("Enter a number: "))

	if num > 1:
		for i in range(2, num):
			if(num % i)== 0:
				print(i,"times", num//i, "is", num)
				break
			else:
				print(num, "is a prime number")


	else:
		print(num,"is not a prime number")


def main():
	isPrime(number)



if __name__ = '__main__':
	isPrime(101);