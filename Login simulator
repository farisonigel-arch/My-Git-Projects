correct_username = "admin"
correct_password = "1234"

max_attempts = 3
attempts = 0

while attempts < max_attempts:
    print("\n--- Login ---")
    username = input("Enter username: ")
    password = input("Enter password: ")

    if username == correct_username and password == correct_password:
        print("Login successful! Welcome,", username)
        break
    else:
        attempts += 1
        print(f"Incorrect credentials. Attempts left: {max_attempts - attempts}")

if attempts == max_attempts:
    print("Too many failed attempts. Access denied.")
