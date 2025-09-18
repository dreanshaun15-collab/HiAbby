import random
import time
from colorama import Fore, Style, init

# initialize colorama
init(autoreset=True)

def compliment_abby():
    compliments = [
        "Abby, your hair looks great today.",
        "Abby, you have a nice smile.",
        "Abby, that color really suits you.",
        "Abby, your laugh is cute.",
        "Abby, you look good in every picture.",
        "Abby, you make casual clothes look stylish.",
        "Abby, your voice is really pleasant.",
        "Abby, you always pick the best outfits.",
        "Abby, your energy makes the day better.",
        "Abby, you have really nice eyes."
    ]
    return random.choice(compliments)

def show_design(text):
    border = "*" * (len(text) + 6)
    print(Fore.CYAN + border)
    print(Fore.MAGENTA + f"** {text} **")
    print(Fore.CYAN + border)

def main():
    print(Fore.YELLOW + "💖 Welcome to the Abby Compliment Generator 💖\n")
    name = input("Type Abby's name to get a compliment: ")

    if name.lower() == "abby":
        print(Fore.GREEN + "\nGenerating compliment...\n")
        time.sleep(1.5)
        comp = compliment_abby()
        show_design(comp)
    else:
        print(Fore.RED + "Sorry, this generator is only for Abby 😉")

if __name__ == "__main__":
    main()
