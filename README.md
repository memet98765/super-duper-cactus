import random
import string

store = {}

def shortlinkproduce(lenght=6):
  characters = string.ascii_letters + string.digits
  code = ''.join(random.choice(characters) for i in range(lenght)

  if code not in store:
    return code

def shorten(long_url)
  short_url = shortlinkproduce()
  store[short_url] = long_url
  return "shortly.py" + code

def widen(orginal_url):
  return store.get(shorten)

url = input("Enter your link")

short = short_url

print("Short Url Is:", short)

orginal = widen(orginal_url)

print("Orginal Url Is:", orginal)
