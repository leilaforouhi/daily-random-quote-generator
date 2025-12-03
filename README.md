import random
import datetime

quotes = [
    "Success is not final; failure is not fatal.",
    "Every moment is a fresh beginning.",
    "Do something today that your future self will thank you for.",
    "Small progress is still progress.",
    "You are stronger than you think."
]

today = datetime.date.today()
picked = random.choice(quotes)

print(f"Today's date: {today}")
print(f"Random Quote: {picked}")
