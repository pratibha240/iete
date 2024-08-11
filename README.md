# iete

import random

def generate_pickup_line():
    lines = [
        "Are you a magician? Because whenever I look at you, everyone else disappears.",
        "Do you have a map? I keep getting lost in your eyes.",
        "Is your name Google? Because you have everything I’ve been searching for.",
        "Do you believe in love at first sight—or should I walk by again?",
        "Are you made of copper and tellurium? Because you're Cu-Te.",
        "If you were a vegetable, you’d be a cute-cumber!",
        "Can I follow you home? Because my parents always told me to follow my dreams.",
        "Do you have a Band-Aid? Because I just scraped my knee falling for you."
    ]

    return random.choice(lines)

# Generate and print a random pickup line
print(generate_pickup_line())
