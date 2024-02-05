FINDING A NUMBER 


num_list = []
for i in range(1,51):
    num_list.append(i)

input_num = int(input("enter a number : "))
def find_num(input_num):
    if input_num in num_list:
        print(input_num,"is in the list.")
    else:
        print(input_num,"is not in the list.")

find_num(input_num)

