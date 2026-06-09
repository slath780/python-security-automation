import os
files = os.listdir()

counter =1
for file in files:
	new_name = f "file{counter}.txt"
	
os.rename(file,new_name)

print(f"{file} -> {new_name}")

counter=counter+1