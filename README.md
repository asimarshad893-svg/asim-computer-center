import pywhatkit as pw
import time

number = "+919453423584   # jisko msg bhejna hai
message = "Hello bhai"     # message
count = 1000                  # jitni baar bhejna ho

for i in range(count):
    pw.sendwhatmsg_instantly(number, message, wait_time=10, tab_close=True)
    time.sleep(15)
