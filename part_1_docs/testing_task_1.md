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
    if card.value = 1:
      # in if statement equality is presented by double equal sign
      return True
    else
    # else must be followed by the double dot. else:
      return False


  dif highest_card(self, card1 card2):
  # dif contains a spelling error. It needs to be: def highest_card(self, card1 card2):
  if card1.value > card2.value:
    # if statement has an indentation error.
    return card
    # it needs to return card1 not card
  else:
    return card2



def cards_total(self, cards):
  # the whole function has an indention error. It does not belong to the CardGame class
  total
  # total value needs to be assign to zero for it work as a counter
  for card in cards:
    total += card.value
    return "You have a total of" + total
  # instead of return it should be return f"You have a total of {total}"
```
