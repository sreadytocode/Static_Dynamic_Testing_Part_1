### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# No semi colon : after else so syntax error also = should be ==
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# def spelled incorrectly hence not a function also 'card' not defined
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# It would come up with an error as it is trying to concatenate a string and an integer object. Should definr total to 0.
# Also indent return back otherwise will be part of the for loop.

def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
