# Array-Assignment
def display_names(names):
    for name in names:
        print(name)

def display_names_reverse(names):
    for name in reversed(names):
        print(name)

# Assign 10 last names to an array
last_names = ["Smith", "Johnson", "Williams", "Jones", "Brown", "Davis", "Miller", "Wilson", "Moore", "Taylor"]

# Display the names
print("Original Order:")
display_names(last_names)

# Display the names in reverse order
print("\nReverse Order:")
display_names_reverse(last_names)
