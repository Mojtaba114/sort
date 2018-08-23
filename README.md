def sort_list(list1):
	i = len(list1)-1
	while i > 0:
		index_max = 0
		j = 0
		while j <= i:
			if list1[j] > list1[index_max]:
				index_max = j
			j+=1
		tmp = list1[index_max]
		list1[index_max] = list1[i]
		list1[i] = tmp
		i -= 1

list1=[2,3,7,1,0,-3,8,-8,10]

sort_list(list1)

print(list1)
print('hi mojtaba')
