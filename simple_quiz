
print("""

 _______          _________ _______   
(  ___  )|\     /|\__   __// ___   )  
| (   ) || )   ( |   ) (   \/   )  |  
| |   | || |   | |   | |       /   )  
| |   | || |   | |   | |      /   /   
| | /\| || |   | |   | |     /   /    
| (_\ \ || (___) |___) (___ /   (_/\  
(____\/_)(_______)\_______/(_______/  
                                      

""")



questions = [
    {
        "qn": "Which mountain is the highest peak in Nepal?",
        "options": ["A. K2", "B. Kangchenjunga", "C. Mount Everest", "D. Lhotse"],
        "answer": "C"
    },
    {
        "qn": "What is the national language of Nepal?",
        "options": ["A. Hindi", "B. Nepali", "C. Tibetan", "D. Bengali"],
        "answer": "B"
    },
    {
        "qn": "Which is the national animal of Nepal?",
        "options": ["A. Tiger", "B. Cow", "C. Elephant", "D. Yak"],
        "answer": "B"
    },
    {
        "qn": "Which river is the longest in Nepal?",
        "options": ["A. Koshi", "B. Gandaki", "C. Karnali", "D. Bagmati"],
        "answer": "C"
    },
    {
        "qn": "Which is the only international airport in Nepal?",
        "options": ["A. Gautam Buddha Airport", "B. Tribhuvan International Airport", "C. Pokhara Airport", "D. Bharatpur Airport"],
        "answer": "B"
    },
    {
        "qn": "In which year did Nepal become a federal democratic republic?",
        "options": ["A. 1990", "B. 2001", "C. 2008", "D. 2015"],
        "answer": "C"
    },
    {
        "qn": "Which festival is considered the biggest in Nepal?",
        "options": ["A. Dashain", "B. Tihar", "C. Holi", "D. Losar"],
        "answer": "A"
    },
    {
        "qn": "Who is considered the founder of modern Nepal?",
        "options": ["A. Prithvi Narayan Shah", "B. Birendra Bir Bikram Shah", "C. Tribhuvan Bir Bikram Shah", "D. Gyanendra Bir Bikram Shah"],
        "answer": "A"
    },
    {
        "qn": "Which city is known as the 'City of Lakes' in Nepal?",
        "options": ["A. Bhaktapur", "B. Pokhara", "C. Lalitpur", "D. Janakpur"],
        "answer": "B"
    },
    {
        "qn": "Which of the following is the national flower of Nepal?",
        "options": ["A. Rose", "B. Lotus", "C. Sunflower", "D. Rhododendron"],
        "answer": "D"
    }
]


def run_quiz():
    score = 0
    for question in questions:
        print(question["qn"])
        for option in question["options"]:
            print(option)
        answer = input("Enter Your answer (A, B, C, D): ").upper()
        if answer == question["answer"]:
            print("Correct, Hooray !!\n")
            score += 1
        else:
            print("Wrong, The correct answer was", question["answer"], "\n")

    print("Your final score is", score)


run_quiz()
