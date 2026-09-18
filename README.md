# voting.py
    age = int(input("Enter your age: "))
    if age >= 18:
        print("You are eligible to vote!")
    elif age > 0:
        years_left = 18 - age
        print(f"You are not eligible to vote. You need to wait {years_left} more year(s).")
    else:
        print("Invalid age. Please enter a positive number.")
    except ValueError:
    print("Invalid input. Please enter a valid number for age.")
