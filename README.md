# Morph-Market-Average-Price
*this script doean't work for the current Morph Market website \n
This script calculates the average price of a particular morph on morph market
# How to use this scrpit
1. enter the morph you'd like to search in the morphs list and the morph you'd like to exclude in the negmorphs list
  morphs=["Ivory","Leopard"]
  negmorphs=["Clown"]
2. If the gene you search has a space, replace it with +
   ex. Instead of "Yellow Belly", type "Yellow+Belly"
4. if you'd like to search a gene in its single form, you have to exclude the super form in the negmorphs list. ex. If I desire to search only the single form Enchi, you need to exclude "Super+Enchi" in the negmorphs list.
  morphs=["Enchi"]
  negmorphs=["Super+Enchi"]
