
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-1.\n",
    "Simple Message: Store a message in a variable, and then print that\n",
    "message."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 325,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "This is first programe of Python Assignment\n"
     ]
    }
   ],
   "source": [
    "message_kashif=\"This is first programe of Python Assignment\"\n",
    "print(message_kashif)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-2. \n",
    "Simple Messages: Store a message in a variable, and print that message.\n",
    "Then change the value of your variable to a new message, and print the new\n",
    "message."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 326,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "This is initial Value of the variable\n",
      "This is updated Value of the variable\n"
     ]
    }
   ],
   "source": [
    "message_value_kashif=\"This is initial Value of the variable\"\n",
    "print(message_value_kashif)\n",
    "message_value_kashif=\"This is updated Value of the variable\"\n",
    "print(message_value_kashif)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-3. \n",
    "Personal Message: Store a person’s name in a variable, and print a message\n",
    "to that person. Your message should be simple, such as, “Hello Eric,\n",
    "would you like to learn some Python today?”"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 327,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello Babar, would you like to learn some Python today?\n"
     ]
    }
   ],
   "source": [
    "name_kashif=\"Babar\"\n",
    "print(\"Hello \"+name_kashif+\", would you like to learn some Python today?\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-4. Name Cases: Store a person’s name in a variable, and then print that person’s\n",
    "name in lowercase, uppercase, and titlecase."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 328,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "shahid afridi\n",
      "SHAHID AFRIDI\n",
      "Shahid Afridi\n"
     ]
    }
   ],
   "source": [
    "person_kashif=\"Shahid Afridi\"\n",
    "print(person_kashif.lower())\n",
    "print(person_kashif.upper())\n",
    "print(person_kashif.title())"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-5. \n",
    "Famous Quote: Find a quote from a famous person you admire. Print the\n",
    "quote and the name of its author. Your output should look something like the\n",
    "following, including the quotation marks:\n",
    "Albert Einstein once said, “A person who never made a\n",
    "mistake never tried anything new.”"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 329,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hazrat Muhammad (PBUH) Said, \"Do not, then , follow your own desires lest you keep away from justice\"\n"
     ]
    }
   ],
   "source": [
    "print(\"Hazrat Muhammad (PBUH) Said, \\\"Do not, then , follow your own desires lest you keep away from justice\\\"\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-6. \n",
    "Famous Quote 2: Repeat Exercise 2-5, but this time store the famous person’s\n",
    "name in a variable called famous_person. Then compose your message\n",
    "and store it in a new variable called message. Print your message."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 330,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hazrat Muhammad (PBUH) Said, \"Do not, then , follow your own desires lest you keep away from justice\"\n"
     ]
    }
   ],
   "source": [
    "famous_person_kashif=\"Hazrat Muhammad (PBUH)\"\n",
    "message_person_kashif=\"\\\"Do not, then , follow your own desires lest you keep away from justice\\\"\"\n",
    "print(famous_person_kashif+\" Said, \"+message_person_kashif)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-7. \n",
    "Stripping Names: Store a person’s name, and include some whitespace\n",
    "characters at the beginning and end of the name. Make sure you use each\n",
    "character combination, \"\\t\" and \"\\n\", at least once.\n",
    "Print the name once, so the whitespace around the name is displayed.\n",
    "Then print the name using each of the three stripping functions, lstrip(),\n",
    "rstrip(), and strip()."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 331,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\tMuhammad Kashif\n",
      "\n",
      "Muhammad Kashif\n",
      "\n",
      "\tMuhammad Kashif\n",
      "Muhammad Kashif\n"
     ]
    }
   ],
   "source": [
    "striping_kashif=\"\\tMuhammad Kashif\\n\"\n",
    "print(striping_kashif)\n",
    "print(striping_kashif.lstrip())\n",
    "print(striping_kashif.rstrip())\n",
    "print(striping_kashif.strip())"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-8. \n",
    "Number Eight: Write addition, subtraction, multiplication, and division\n",
    "operations that each result in the number 8. Be sure to enclose your operations\n",
    "in print statements to see the results. You should create four lines that look\n",
    "like this:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 332,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "8\n",
      "8\n",
      "8\n",
      "8\n"
     ]
    }
   ],
   "source": [
    "print(4+4)\n",
    "print(13-5)\n",
    "print(2*4)\n",
    "print(80//10)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-9. \n",
    "Favorite Number: Store your favorite number in a variable. Then, using\n",
    "that variable, create a message that reveals your favorite number. Print that\n",
    "message."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 333,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " My Favourite No is 23\n"
     ]
    }
   ],
   "source": [
    "fav_kashif=23\n",
    "print(\" My Favourite No is \"+str(fav_kashif))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-1. \n",
    "Names: Store the names of a few of your friends in a list called names. Print\n",
    "each person’s name by accessing each element in the list, one at a time."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 334,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sabir\n",
      "Shahid\n",
      "Zeeshan\n"
     ]
    }
   ],
   "source": [
    "friends_kashif=['Sabir','Shahid','Zeeshan']\n",
    "print(friends_kashif[0])\n",
    "print(friends_kashif[1])\n",
    "print(friends_kashif[2])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-2. \n",
    "Greetings: Start with the list you used in Exercise 3-1, but instead of just\n",
    "printing each person’s name, print a message to them. The text of each message\n",
    "should be the same, but each message should be personalized with the\n",
    "person’s name."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 335,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sabir You are my good friend\n",
      "Shahid You are my good friend\n",
      "Zeeshan You are my good friend\n"
     ]
    }
   ],
   "source": [
    "print(friends_kashif[0]+\" You are my good friend\")\n",
    "print(friends_kashif[1]+\" You are my good friend\")\n",
    "print(friends_kashif[2]+\" You are my good friend\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-3.\n",
    " Your Own List: Think of your favorite mode of transportation, such as a\n",
    "motorcycle or a car, and make a list that stores several examples. Use your list\n",
    "to print a series of statements about these items, such as “I would like to own a\n",
    "Honda motorcycle.”"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 336,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "I goes to school on Honda Prider\n",
      "I goes to college on Suzuki Mehran\n",
      "I goes to universtiy on Honda City\n"
     ]
    }
   ],
   "source": [
    "vehicles_kashif=['Honda Prider', 'Suzuki Mehran', 'Honda City']\n",
    "print(\"I goes to school on \"+vehicles_kashif[0])\n",
    "print(\"I goes to college on \"+vehicles_kashif[1])\n",
    "print(\"I goes to universtiy on \"+vehicles_kashif[2])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-4. \n",
    "Guest List: If you could invite anyone, living or deceased, to dinner, who\n",
    "would you invite? Make a list that includes at least three people you’d like to\n",
    "invite to dinner. Then use your list to print a message to each person, inviting\n",
    "them to dinner."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 337,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Dear Sabir you are invited to dinner tonight\n",
      "Dear Shahid you are invited to dinner tonight\n",
      "Dear Zeeshan you are invited to dinner tonight\n",
      "Dear Amir you are invited to dinner tonight\n",
      "Dear Adnan you are invited to dinner tonight\n"
     ]
    }
   ],
   "source": [
    "guests_kashif=['Sabir','Shahid','Zeeshan','Amir','Adnan']\n",
    "print(\"Dear \"+guests_kashif[0]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[1]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[2]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[3]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[4]+\" you are invited to dinner tonight\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-5. Changing Guest List: You just heard that one of your guests can’t make the\n",
    "dinner, so you need to send out a new set of invitations. You’ll have to think of\n",
    "someone else to invite.\n",
    "• Start with your program from Exercise 3-4. Add a print statement at the\n",
    "end of your program stating the name of the guest who can’t make it.\n",
    "• Modify your list, replacing the name of the guest who can’t make it with\n",
    "the name of the new person you are inviting.\n",
    "• Print a second set of invitation messages, one for each person who is still\n",
    "in your list."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 338,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Shahid is not able to attend dinner tonight\n",
      "Imran will attend dinner tonight\n",
      "Dear Sabir you are invited to dinner tonight\n",
      "Dear Imran you are invited to dinner tonight\n",
      "Dear Zeeshan you are invited to dinner tonight\n",
      "Dear Amir you are invited to dinner tonight\n",
      "Dear Adnan you are invited to dinner tonight\n"
     ]
    }
   ],
   "source": [
    "print(guests_kashif[1]+\" is not able to attend dinner tonight\")\n",
    "guests_kashif[1]=\"Imran\"\n",
    "print(guests_kashif[1]+\" will attend dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[0]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[1]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[2]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[3]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[4]+\" you are invited to dinner tonight\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-6. More Guests: You just found a bigger dinner table, so now more space is\n",
    "available. Think of three more guests to invite to dinner.\n",
    "• Start with your program from Exercise 3-4 or Exercise 3-5. Add a print\n",
    "statement to the end of your program informing people that you found a\n",
    "bigger dinner table.\n",
    "• Use insert() to add one new guest to the beginning of your list.\n",
    "• Use insert() to add one new guest to the middle of your list.\n",
    "• Use append() to add one new guest to the end of your list.\n",
    "• Print a new set of invitation messages, one for each person in your list."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 339,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Sabir', 'Imran', 'Zeeshan', 'Amir', 'Adnan']\n"
     ]
    }
   ],
   "source": [
    "print(guests_kashif)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 340,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Dear friends, We found a bigger dinner table. So I am inviting three more friends.\n",
      "Dear Kamran you are invited to dinner tonight\n",
      "Dear Sabir you are invited to dinner tonight\n",
      "Dear Imran you are invited to dinner tonight\n",
      "Dear Zeeshan you are invited to dinner tonight\n",
      "Dear Ahsan you are invited to dinner tonight\n",
      "Dear Amir you are invited to dinner tonight\n",
      "Dear Adnan you are invited to dinner tonight\n",
      "Dear Moeen you are invited to dinner tonight\n"
     ]
    }
   ],
   "source": [
    "print(\"Dear friends, We found a bigger dinner table. So I am inviting three more friends.\")\n",
    "guests_kashif.insert(0,'Kamran')\n",
    "guests_kashif.insert(4,'Ahsan')\n",
    "guests_kashif.append('Moeen')\n",
    "print(\"Dear \"+guests_kashif[0]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[1]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[2]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[3]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[4]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[5]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[6]+\" you are invited to dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[7]+\" you are invited to dinner tonight\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-7. Shrinking Guest List: You just found out that your new dinner table won’t\n",
    "arrive in time for the dinner, and you have space for only two guests.\n",
    "• Start with your program from Exercise 3-6. Add a new line that prints a\n",
    "message saying that you can invite only two people for dinner.\n",
    "• Use pop() to remove guests from your list one at a time until only two\n",
    "names remain in your list. Each time you pop a name from your list, print\n",
    "a message to that person letting them know you’re sorry you can’t invite\n",
    "them to dinner.\n",
    "• Print a message to each of the two people still on your list, letting them\n",
    "know they’re still invited.\n",
    "• Use del to remove the last two names from your list, so you have an empty\n",
    "list. Print your list to make sure you actually have an empty list at the end\n",
    "of your program."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 341,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sorry Friends, Only two Friends can attend the Dinner\n",
      "Sorry Kamran You can't attend the dinner\n",
      "Sorry Sabir You can't attend the dinner\n",
      "Sorry Imran You can't attend the dinner\n",
      "Sorry Zeeshan You can't attend the dinner\n",
      "Sorry Ahsan You can't attend the dinner\n",
      "Sorry Amir You can't attend the dinner\n",
      "Dear Adnan you can attend the dinner tonight\n",
      "Dear Moeen you can attend the dinner tonight\n",
      "[]\n"
     ]
    }
   ],
   "source": [
    "print(\"Sorry Friends, Only two Friends can attend the Dinner\")\n",
    "guest1_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest1_removed+\" You can't attend the dinner\")\n",
    "guest2_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest2_removed+\" You can't attend the dinner\")\n",
    "guest3_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest3_removed+\" You can't attend the dinner\")\n",
    "guest4_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest4_removed+\" You can't attend the dinner\")\n",
    "guest5_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest5_removed+\" You can't attend the dinner\")\n",
    "guest6_removed=guests_kashif.pop(0)\n",
    "print(\"Sorry \"+guest6_removed+\" You can't attend the dinner\")\n",
    "print(\"Dear \"+guests_kashif[0]+\" you can attend the dinner tonight\")\n",
    "print(\"Dear \"+guests_kashif[1]+\" you can attend the dinner tonight\")\n",
    "del guests_kashif[0]\n",
    "del guests_kashif[0]\n",
    "print(guests_kashif)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3-9. Dinner Guests: Working with one of the programs from Exercises 3-4\n",
    "through 3-7 (page 46), use len() to print a message indicating the number\n",
    "of people you are inviting to dinner."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 342,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "i am inviting 5 Poeple.\n"
     ]
    }
   ],
   "source": [
    "guests_count_kashif=['Sabir','Shahid','Zeeshan','Amir','Adnan']\n",
    "\n",
    "print(\"i am inviting \"+str(len(guests_count_kashif))+\" Poeple.\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "4-1. Pizzas: Think of at least three kinds of your favorite pizza. Store these\n",
    "pizza names in a list, and then use a for loop to print the name of each pizza.\n",
    "• Modify your for loop to print a sentence using the name of the pizza\n",
    "instead of printing just the name of the pizza. For each pizza you should\n",
    "have one line of output containing a simple statement like I like pepperoni\n",
    "pizza.\n",
    "• Add a line at the end of your program, outside the for loop, that states\n",
    "how much you like pizza. The output should consist of three or more lines\n",
    "about the kinds of pizza you like and then an additional sentence, such as\n",
    "I really love pizza!"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 343,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Chicago Pizza\n",
      "Siclian Pizza\n",
      "Greek Pizza\n",
      "Deep Disha Pizza\n",
      "I like to Eat Chicago Pizza everytime\n",
      "I like to Eat Siclian Pizza everytime\n",
      "I like to Eat Greek Pizza everytime\n",
      "I like to Eat Deep Disha Pizza everytime\n",
      "I love Pizza\n"
     ]
    }
   ],
   "source": [
    "pizza_kashif=['Chicago Pizza','Siclian Pizza','Greek Pizza','Deep Disha Pizza']\n",
    "for j in range(0,len(pizza_kashif)):\n",
    "    print(pizza_kashif[j])\n",
    "for i in range(0,len(pizza_kashif)):\n",
    "    print(\"I like to Eat \"+pizza_kashif[i]+\" everytime\")\n",
    "print(\"I love Pizza\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "4-2. Animals: Think of at least three different animals that have a common characteristic.\n",
    "Store the names of these animals in a list, and then use a for loop to\n",
    "print out the name of each animal.\n",
    "• Modify your program to print a statement about each animal, such as\n",
    "A dog would make a great pet.\n",
    "• Add a line at the end of your program stating what these animals have in\n",
    "common. You could print a sentence such as Any of these animals would\n",
    "make a great pet!"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 344,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "goat\n",
      "cow\n",
      "buffalow\n",
      "goat is a Halal Pet\n",
      "cow is a Halal Pet\n",
      "buffalow is a Halal Pet\n",
      "All these Animals give Milk\n"
     ]
    }
   ],
   "source": [
    "animals_kashif=['goat','cow','buffalow']\n",
    "for a in range(0,len(animals_kashif)):\n",
    "    print(animals_kashif[a])\n",
    "for b in range(0,len(animals_kashif)):\n",
    "    print(animals_kashif[b]+\" is a Halal Pet\")\n",
    "print(\"All these Animals give Milk\")"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3.10.5 64-bit",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.5"
  },
  "orig_nbformat": 4,
  "vscode": {
   "interpreter": {
    "hash": "afb734500600fd355917ca529030176ea0ca205570884b88f2f6f7d791fd3fbe"
   }
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
