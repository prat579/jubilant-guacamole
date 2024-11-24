print('몇 개의 변수를 사용하실건가요?')
a = input()
if '2' or '3' in a:
	if '2' in a:
		print('X,Y의 갑을 입력하시오')
		x = input()
		y = input()
		print('곱할려면 1 나눌려면 2를 누르시오.')
		b = input()
		if '1' in b:
			print(x*y)
		if '2' in b:
			print(x/y)
	if '3' in a:
		print('X,Y,Z의 갑을 입력하십시오.')
		x = input()
		y = input()
		z = input()
		print('곱할려면 1 나눌려면 2를 누르시오.')
		b = input()
		if '1' or '2' in b:
			if '1' in b:
				print(x*y*z)
			if '2' in b:
				print(x/y/z