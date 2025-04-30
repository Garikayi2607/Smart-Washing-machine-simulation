# Smart-Washing-machine-simulation

Objective

build a simulation of a smart washing machine with features such as :
         - Wash Cycle selection
         - Timer and water level control
         - Predictive fabric type recognition
         - Efficiency scoring

Technologies and Libraries employed to reach this goal:
         - sklearn.model_selection
         - sklearn.ensemble
         - sklearn.matric
Simulated Washing Machine Class.

class WashingMachine:
 def__init__(self):
 self.state="OFF"
 self.cycle="Normal"
 self.timer=30
 self.water_level="Medium"
 self.fabric_type="Cotton"

 def power_on (self):
     self.state="ON"
     print ("Washing machine is ON.")

def power_off (self):
    self.state= "OFF"
    print ("Washing machine is OFF.")

def set_cycle(self,cycle):
    self.cycle=cycle
    print(f"cycle set to {cycle}.")

def set_timer(self, minutes):
    self.timer=minutes
    print (f"Timer set to {minutes}minutes.")

def set_water_level=level
    print (f "Water level set to {level}.")

def set_fabric_type (self,fabric):
    self.fabric_type+fabric
    print (f"Fabrictype set to {fabric}.")

def start (self):
    if self.state=="OFF"
    print ("Power is OFF. Cannot start.")

  else:
       print (f"starting {self.cycle}wash cycle for {self.fabric_type}fabric.")
       for i in range (o,self, timer, 10):
       print (f"...washing({i+10}/{self.timer}minutes)")time.sleep(1)
       print ("Washing complete.")

Recommendations

def
recommend_settings(fabric_type):
settings={'Cotton':{'Normal',40,'High'),
          'Silk': ('Delicate', 20, 'Low'),
          'Wool': ('Wool',30, 'Medium')}
          return
          settings.get(fabric_type,('Normal',30,'Medium'))

Execution

# Predict fabric from new sensor input
predicted_fabric=model.predict([2,1,  120]] [0]

#Recommended settings
cycle, timer, water=recommended_settings(predicted_fabric)

#create and run washing machine
wm= WashingMachine ()
wm.power.on()
wm.set_fabric_type(predicted_fabric)
wm.set_cycle(cycle)
wm.set_timer(timer)
wm.set_water_level(water)
wm.start()
wm.power_off()

Evaluation Metrics
Accuracy and classification reportfrom sklearn.metrics

Recommendations
Use real sensor data for bettermodel performance
Incorporate temperature sensing and detergent amount optimization
Add anomaly detection for machine errors

Future Steps
Data Expansion: Collect real-world sensor data for better accuracy
build an app tocontrol and monitor remotely
Intergration
Smart Features Add AI  voice assistant and predictive maintenance using time series data


















          
          


















     
     
