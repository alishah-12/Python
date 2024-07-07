# Python
"""
import qrcode as qr
img = qr.make("https://www.youtube.com/watch?v=RnP7NqgKydg")
img.save("w3school.png")

import qrcode as qr
img = qr.make("https://web.whatsapp.com/")
img.save("whatsapp.png")
"""

email = input("Enter your email: ")
if ("@" in email):
    print("pass")
else:
    print("Wrong email")
