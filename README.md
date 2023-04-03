# CodeClause-random-password-genarator
# The Password generator tool creates a random and customized password for users that helps them to create a strong password which provides greater security.

import random
import string
def generate_password(length):
    all_chars = string.ascii_letters + string.digits
    password = ''.join(random.sample(all_chars, length))
    return password
password = generate_password(12)
print("password is: ",password)
