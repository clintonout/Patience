# Patience
import time
import random

class Simulation:
    def __init__(self):
        self.heart_rate = 70  # Starting heart rate in beats per minute
        self.breath_holding = False
        self.sitting_still = True

    def hold_breath(self, duration):
        print("Holding breath...")
        self.breath_holding = True
        time.sleep(duration)
        self.breath_holding = False
        print("Breath released.")

    def control_heart_rate(self, target_rate, duration):
        print("Controlling heart rate...")
        start_time = time.time()
        while time.time() - start_time < duration:
            self.heart_rate = target_rate
            time.sleep(1)
            print(f"Heart rate: {self.heart_rate} bpm")
        print("Heart rate control complete.")

    def sit_still(self, duration):
        print("Sitting still...")
        self.sitting_still = True
        time.sleep(duration)
        print("Finished sitting still.")

def main():
    simulation = Simulation()

    # Simulate holding breath for 40 minutes (2400 seconds)
    simulation.hold_breath(2400)

    # Simulate controlling heart rate for 40 minutes
    simulation.control_heart_rate(60, 2400)

    # Simulate sitting still for 40 minutes
    simulation.sit_still(2400)

if __name__ == "__main__":
    main()import time
import random

class Simulation:
    def __init__(self):
        self.heart_rate = 70  # Starting heart rate in beats per minute
        self.breath_holding = False
        self.sitting_still = True

    def hold_breath(self, duration):
        print("Holding breath...")
        self.breath_holding = True
        time.sleep(duration)
        self.breath_holding = False
        print("Breath released.")

    def control_heart_rate(self, target_rate, duration):
        print("Controlling heart rate...")
        start_time = time.time()
        while time.time() - start_time < duration:
            self.heart_rate = target_rate
            time.sleep(1)
            print(f"Heart rate: {self.heart_rate} bpm")
        print("Heart rate control complete.")

    def sit_still(self, duration):
        print("Sitting still...")
        self.sitting_still = True
        time.sleep(duration)
        print("Finished sitting still.")

def main():
    simulation = Simulation()

    # Simulate holding breath for 40 minutes (2400 seconds)
    simulation.hold_breath(2400)

    # Simulate controlling heart rate for 40 minutes
    simulation.control_heart_rate(60, 2400)

    # Simulate sitting still for 40 minutes
    simulation.sit_still(2400)

if __name__ == "__main__":
    main()import time
import random

class Simulation:
    def __init__(self):
        self.heart_rate = 70  # Starting heart rate in beats per minute
        self.breath_holding = False
        self.sitting_still = True

    def hold_breath(self, duration):
        print("Holding breath...")
        self.breath_holding = True
        time.sleep(duration)
        self.breath_holding = False
        print("Breath released.")

    def control_heart_rate(self, target_rate, duration):
        print("Controlling heart rate...")
        start_time = time.time()
        while time.time() - start_time < duration:
            self.heart_rate = target_rate
            time.sleep(1)
            print(f"Heart rate: {self.heart_rate} bpm")
        print("Heart rate control complete.")

    def sit_still(self, duration):
        print("Sitting still...")
        self.sitting_still = True
        time.sleep(duration)
        print("Finished sitting still.")

def main():
    simulation = Simulation()

    # Simulate holding breath for 40 minutes (2400 seconds)
    simulation.hold_breath(2400)

    # Simulate controlling heart rate for 40 minutes
    simulation.control_heart_rate(60, 2400)

    # Simulate sitting still for 40 minutes
    simulation.sit_still(2400)

if __name__ == "__main__":
    main()
