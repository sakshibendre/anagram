# anagram
Anagram program in python
s1 = input("enter 1st string")
s2 = input("enter 2nd string")

if len(s1) != len(s2):
	print("strings are not anagram")
else:
	s1=sorted(s1)
	s2=sorted(s2)
	if s1==s2:
		print("strings are angram")
	else:
		print("strings are not anagram")
