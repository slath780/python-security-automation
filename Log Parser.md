file = open("name_file")

content = file.read()

failed = content.count("Login failed")

print(f"Failed logins: {failed}")

file.close()
