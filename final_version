from sense_hat import SenseHat
from time import sleep
sense = SenseHat()
pixel_list = sense.get_pixels()

def aleksander():
  sense.set_rotation(270)
  W = (255, 255, 255)
  B = (0, 0, 0)
  p = (51, 0, 102)
  b = (0, 0, 255)
  y = (255, 255, 0)
  o = (255, 69, 0)
  r = (255, 0, 0)
  
  def getTemperature():
    temperature = round(sense.get_temperature())
    if temperature <= 31:
      back_colour = p
    elif 31 < temperature <= 32:
      back_colour = b
    elif 32 < temperature <= 33:
      back_colour = y
    elif 33 < temperature <= 34:
      back_colour = o
    elif temperature > 34:
      back_colour = r
    
    speed = 0.06
    sense.show_message("The Temp is: " + str(temperature) + "C", speed, text_colour = W, back_colour =  back_colour)
    return temperature

  temperature = getTemperature()
  myImage = [
      B, B, W, W, W, W, B, B,
      B, B, W, B, B, W, B, B,
      B, B, W, B, B, W, B, B,
      B, B, W, B, B, W, B, B,
      B, B, W, B, B, W, B, B,
      B, W, B, B, B, B, W, B,
      B, W, B, B, B, B, W, B,
      B, B, W, W, W, W, B, B,
      ]
  if temperature <= 31:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
  elif 31 < temperature <= 32:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
    sense.set_pixels(myImage)
    sleep(1)
    for c in range(35,37):
      myImage[c] = b    
  
  elif 32 < temperature <= 33:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
    sense.set_pixels(myImage)
    sleep(1)
    for c in range(35,37):
      myImage[c] = b
      
    sense.set_pixels(myImage)
    sleep(1)
    for v in range(27,29):
      myImage[v] = y
      
  elif 33 < temperature <= 34:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
    sense.set_pixels(myImage)
    sleep(1)
    for c in range(35,37):
      myImage[c] = b
      
    sense.set_pixels(myImage)
    sleep(1)
    for v in range(27,29):
      myImage[v] = y
      
    sense.set_pixels(myImage)
    sleep(1)
    for i in range(19,21):
      myImage[i] = o
      
  elif 34 < temperature <= 39:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
    sense.set_pixels(myImage)
    sleep(1)
    for c in range(35,37):
      myImage[c] = b
      
    sense.set_pixels(myImage)
    sleep(1)
    for v in range(27,29):
      myImage[v] = y
      
    sense.set_pixels(myImage)
    sleep(1)
    for i in range(19,21):
      myImage[i] = o
    
    sense.set_pixels(myImage)
    sleep(1)
    for n in range(11,13):
      myImage[n] = r
      
  elif temperature >= 40:
    for z in range(50,54):
      myImage[z] = p
    for x in range(42,46):
      myImage[x] = p
      
    sense.set_pixels(myImage)
    sleep(1)
    for c in range(35,37):
      myImage[c] = b
      
    sense.set_pixels(myImage)
    sleep(1)
    for v in range(27,29):
      myImage[v] = y
      
    sense.set_pixels(myImage)
    sleep(1)
    for i in range(19,21):
      myImage[i] = o
    
    sense.set_pixels(myImage)
    sleep(1)
    for n in range(11,13):
      myImage[n] = r
    
    sense.set_pixels(myImage)
    sleep(1)
    for n in range(2,6):
      myImage[n] = r
      myImage[9] = r
      myImage[14] = r
      myImage[16] = r
      myImage[22] = r
      
  sense.set_pixels(myImage)
  sleep(3)

aleksander()
