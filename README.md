weight = float(input("Weight in kg:"))
activity_level = input("low/medium/high:")

if activity_level == "low":
    water_intake = weight * 0.033
    print("Recommend daily water intake", water_intake, "liters")

elif activity_level == "medium":
    water_intake = weight * 0.04
    print("Recommend daily water intake", water_intake, "liters")

elif activity_level == "high":
    water_intake = weight * 0.045
    print("Recommend daily water intake", water_intake, "liters")

else:
    print("nothing")
