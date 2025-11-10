from datetime import datetim
import random

def new_things_every_day_17():
    now = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    line = random.choice([
        "Commit today — future you will thank you.",
        "Keep learning, keep building.",
        "Daily effort compounds into mastery.",
        "Code now, shine later.",
        "Each commit writes your story."
    ])
    print(f"[#17] {line} — {now}")

if __name__ == "__main__":
    new_things_every_day_17()
