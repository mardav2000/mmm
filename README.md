import random
print("""Hello ,We are going to play little game called 'Mad Libs',
just type what is needed and you will have some funny story
Lets start """)
x=random.randint(0,2)
if x==0:
    Number=input("Number: ")
    Measure_of_time=input("Measure of time: ")
    Mode_of_Transportation=input("Mode od transportation: ")
    Adjective=input("Adjective:  ")
    Adjective2=input("Adjective2: ")
    Noun=input("Noun: ")
    Color=input("Color: ") 
    Part_of_the_Body=input('Part of the body: ')
    Verb=input("Verb: ")
    Number2=input("Number2: ")
    Noun2=input("Noun2: ")
    Noun3=input("Noun3: ")
    Part_of_the_Body2=input("Part_of_the_Body2: ")
    Verb2=input("Verbr: ")
    Noun4=input("Noun4: ")
    Adjective3=input("Adjective3: ")
    Silly_Word=input("Silly_Word: ")
    print(f'''It was about {Number} {Measure_of_time} ago when I arrived at the hospital in a {Mode_of_Transportation}.
    The hospital is a/an {Adjective} place, there are a lot of {Adjective2} {Noun} here.
    There are nurses here who have {Color} {Part_of_the_Body}.
    If someone wants to come into my room I told them that they have to {Verb}first.
    I've decorated my room with {Number2} {Noun2}.
    Today I talked to a doctor and they were wearing a {Noun3} on their {Part_of_the_Body2}.
    I heard that all doctors {Verb} {Noun4} every day for breakfast.
    The most { Adjective3} thing about being in the hospital is the {Silly_Word} {Noun} !''')
elif x==1:
    Proper_Noun_Person_Name=input("Proper_Noun_Person_Name: ")
    Noun=input("Noun: ")
    Adjective_Feeling=input ('Adjective_Feeling: ')
    Verb=input('Verb: ')
    Adjective_Feeling2=input('Adjective_Feeling2:  ')
    Animal=input('Animal: ')
    Verb2=input('Verb2: ')
    Color=input("Color: ")
    Verb_ending_in_ing=input('Verb_ending_in_ing: ')
    Adverb_ending_in_ly=input('Adverb_ending_in_ly: ')
    Number=input('Number: ')
    Measure_of_Time=input('Measure_of_Time: ')
    Color2=input('Color2: ')
    Animal2=input('Animal2: ')
    Number2=input('Number2: ')
    Silly_Word=input("Silly_Word: ")
    Noun2=input('Noun2: ')
    print(f'''This weekend I am going camping with {Proper_Noun_Person_Name}. I packed my lantern, sleeping bag, and {Noun}.
    I am so {Adjective_Feeling} to {Verb} in a tent. I am {Adjective_Feeling2} we might see a(n) {Animal},
    I hear they’re kind of dangerous. While we’re camping, we are going to hike, fish, and {Verb2}. 
    I have heard that the {Color} lake is great for {Verb_ending_in_ing}. 
    Then we will {Adverb_ending_in_ly} hike through the forest for {Number} {Measure_of_Time}. 
    If I see a {Color2} {Animal2} while hiking, I am going to bring it home as a pet!
    At night we will tell {Number2} {Silly_Word} stories and roast {Noun2} around the campfire!!''')
elif x==2:
    Proper_Noun_Persons_Name=input("Proper_Noun_Persons_Name: ")
    Adjective=input("Adjective: ")
    Color=input("Color: ")
    Animal=input("Animal: ")
    Place=input('Place: ')
    Adjective2=input('Adjective: ')
    Magical_Creature_Plural=input('Magical_Creature_Plural: ')
    Adjective3=input('Adjective3: ')
    Magical_Creature_Plural2=input('Magical_Creature_Plural2: ')
    Room_in_a_House=input('Room_in_a_House: ')
    Noun=input('Noun: ')
    Noun2=input('Noun2: ')
    Noun_Plural3=input('Noun_Plural3: ')
    Adjective4=input('Adjective4: ')
    Noun_Plural4=input('Noun_Plural4: ')
    Number=input('Number: ')
    Measure_of_time=input('Measure_of_time: ')
    Verb_ending_in_ing=input('Verb_ending_in_ing: ')
    Adjective5=input('Adjective5: ')
    Noun5=input('Noun5: ')
    print(f'''Dear {Proper_Noun_Persons_Name}, I am writing to you from a {Adjective} castle in an enchanted forest.
    I found myself here one day after going for a ride on a {Color} {Animal} in {Place}. 
    There are {Adjective2} {Magical_Creature_Plural} and {Adjective3} {Magical_Creature_Plural2} here!
    In the {Room_in_a_House} there is a pool full of {Noun}.
    I fall asleep each night on a {Noun2} of {Noun_Plural3} and dream of {Adjective4}  {Noun_Plural4}. 
    It feels as though I have lived here for {Number} {Measure_of_time}.
    I hope one day you can visit, although the only way to get here now is {Verb_ending_in_ing} on a {Adjective5} {Noun5}!!''')
    
