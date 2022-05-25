
# Hangman Project - Ai Core

So here's the thing - I initially had no clue how to code in Python and my R knowledge was very rusty from my uni days. I do, however,fondly recall the stress of finding where I needed to add a semi colon or remove a full stop - which this experience has brought me back to.
But starting on Ai Core and using Solo Learn for the moments my 8 month old won't let me sit at my desktop, gave me a chance to learn Python from scratch, so here I present my first project; Hangman.

And here we are - with searching, many iterations and moments of joy (as well as the crying little guy who did not care I'm in the middle of a career/identity crisis) Hangman was complete.

Have fun with it if you'd like to try it out!

------------------------------------------------------

# Milestone 1
It started with setting up my workspace and getting familiar with Visual Code, the terminal and re-aquainting myself with using a mac (I'm a Windows/Android lady!). I went through the prerequisite modules on the Ai Core portal which helped - particularly with how to apply my skills that I had previously learned on Solo Learn.

After watching a guide on how to get the repositary from Github, I mapped out which skills I would need and played about each day to see if they would give the right output. 
            
       def ask_letter(self):
        while True: 
            letter = input('Enter a single character : ') # Asks user for input
            letter = letter.lower() # Changes input to lowercase  
            len(letter) == 1 #Letter length should only be one
            if len(letter) > 1: 
                print ("Please, enter just one character") #prompts user to re-enter letter and restarts the loop
            elif letter in self.list_letters: # Checks if letter has already been entered by checking if it is in list
                print(f'{letter} has already been tried') #lets user know it's already been tried and restarts the loop
            else:
                break

I was able to fill in the ask_letter method by defining the ask_letter function. This asks for an input and checks to see if the letter is a single character. Ways I could have improved this was to add extra parameters such as checking if the character was actually a letter. Once it passed both checks,the check_letter method is called.

# Milestone 2

Ask letter function had to be mapped out and it was interesting to see how others had coded theirs yet still worked.



Insert screenshot of what you have built working.

# Milestone 3


# Milestone 4
For bonus points, I searched how to add graphics to my Hangman game and adjusting  it to my code, which thankfully wasn't difficult as i knew my code inside out by this point. 

##(insert image here)

Learning how to use github has been a journey. As can be seen with the multiple versions of this document, I've learned to read instructions better, understand what a repo is, how to create new branches and appreciate the need for it all! Now, how to add screenshots of my code to this file...


# Conclusions


