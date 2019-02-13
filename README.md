# while-true-practaic
while true 判斷成績級數，並讓使用者選擇是否繼續執行或離開
# -*- coding: UTF-8 -*-
while True:
	while True:
		score = int(input('請輸入學生成績：'))
		if 0 <= score <=100:
			if 90 <= score <=100:
				print("A")
				break
			elif 80 <= score <90:
				print("B")
				break
			elif 70 <= score < 80:
				print("C")
				break
			elif 60 <= score < 70:
				print("D")
				break
			else:
				print("E")
				break
		else:
			print("輸入錯誤,請重新輸入！")
	
	while True:
		str1 = raw_input("是否繼續查詢(y/n):")
		if str1 == 'n':
			exit()
		elif str1 == 'y':
			break
		else:
			print("輸入錯誤，請重新輸入！")
	
