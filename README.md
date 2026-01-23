super-duper-cactus (hahaha)

def shortlink(short):
  return short 
  
link = []
url = input("Enter your link here: ")
link.append(url)
  
number = 0
with open("links.txt", "a") as file:
    file.write(f"{number} -> {link[0]}\n")
  for i in file:
    num += 1
    

with open("links.txt", "r") as file:
    content = file.read()
    print(content)

  for i in file:
    i == link
    link == shorten
    shorten += 1

    
chatgpt's way
import random
import string

def sortlink(short):
    return short


def generate_short():
    return ''.join(random.choice(string.ascii_letters) for _ in range(5))


link = []
url = input("Enter your link here: ")
link.append(url)

shorten = generate_short()

with open("links.txt", "a") as file:
    file.write(f"{shorten} -> {link[0]}\n")

with open("links.txt", "r") as file:
    content = file.read()
    print("\nSaved links:")
    print(content)