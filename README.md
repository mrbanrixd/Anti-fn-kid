# A short time delay when ping is high or low
if asf_ping < 300 :
  time.sleep(2)
elif asf_ping > 300 :
  time.sleep(4)
else :
  time.sleep(3)
