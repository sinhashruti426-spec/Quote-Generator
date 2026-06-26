# Quote-Generator
import random
def generate_quote():
    quotes=["A lot will go wrong before everything goes right",
    "Do it for your future self",
    "Mistake are meant to guide you,not to define you",
    "There is a seat waiting for you at tables you haven't even seen",
    "you are what you do, not what you say you'll do"]
    choice=input("Do you want to see a quote?").lower()
    if(choice=="yes"):
        lesson=random.choice(quotes)
        print(lesson)
    elif(choice=="no"):
        print("okayyy")
        print(" o     o")
        print("    |    ")
        print("   ____   ")
    elif(choice=="maybe"):
        print("Do i take it as no? or yes?")
        s=input("yes or no??")
        if(s=="yes"):
            lesson=random.choice(quotes)
            print(lesson)
        elif(s=="no"):
            print("no worry i got you!!")


generate_quote()
