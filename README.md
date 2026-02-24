import random
import string

store = {}

def shortlinkproduce(lenght=6):
  characters = string.ascii_letters + string.digits
  
  while True:
    code = ''.join(random.choice(characters) for i in range(lenght))

    if code not in store:
      return code

def shorten(long_url):
  code = shortlinkproduce()
  store[code] = long_url
  return "shortly.py" + code

def widen(short_url):
  code = short_url.split("/")[-1]
  return store.get(code)

url = input("Enter your link: ")

short = shorten(url)

print("Short Url Is:", short)

orginal = widen(short)

print("Orginal Url Is:", orginal)
