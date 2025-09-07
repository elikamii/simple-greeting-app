import datetime

# A simple function to greet a user by name.
def greet_user(name):
    """Prints a greeting message for the user, including the current time."""
    current_time = datetime.datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    print(f"Hello, {name}! Welcome to our application.")
    print(f"The current time is {current_time}.")

# Example usage
if __name__ == "__main__":
    user_name = "Alice"  # You can change this to any name
    greet_user(user_name)
