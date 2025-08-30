# app.py
greetings = ["hello", "hi", "hey", "greetings"]
goodbyes = ["bye", "goodbye", "see you"]
# The conversation will run for 5 turns at most
for i in range(3):
    user_input = input("You: ").lower()
        if user_input in greetings:
        print("AI: Hello! How can I help you?")
    elif user_input in goodbyes:
        print("AI: Goodbye!")
        break
    else:
        print("AI: I am learning! Tell me more.")
else:
    print("AI: That was fun! Catch you later.")
