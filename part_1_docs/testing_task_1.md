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


  def check_for_ace(self, card):
    # if card.value = 1:
      return True
    # else
      return False
  # line 21 should have 2 == instead of =
  # line 23 missing a colon after else

  # dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    # return card
  else:
    return card2
  # line 27 def is mis spelled "dif"
  # line 30 card should be card1


def cards_total(self, cards):
  # total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  # line 36 "total" does not have a value should = 0
  # line 40 is not indented correctly
  # line 41 has not been concastinated
```
