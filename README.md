# Car-game
speed = 0
distance = 0
finish = 100

print("🏁 Welcome to Car Racing Game 🏁")

while distance < finish:
    print("Speed:", speed, "| Distance:", distance)
    choice = input("Press (a) to accelerate: ")

    if choice == "a":
        speed += 10
        distance += speed

print("🎉 You Win! The car reached the finish line!")