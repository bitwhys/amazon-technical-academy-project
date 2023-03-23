# Basic requirements

For Step 1, you will implement some initial functionality for the T-Shirt store. You will need knowledge from Modules
1-4 of the prerequisites curriculum to do so. The first thing you’ll build will be the store’s greeting and main menu.

When the application first starts, the store should greet and prompt the shopper for their name as follows:

`Hello. Please enter your name:`

After the shopper types in their name, for example ATA Shopper, they should be greeted with the following:

`Welcome ATA Shopper to T-Shirt Mart`

After that, the main shop menu should be displayed, and look like this:

```
--Main Menu--
Select an option using one of the numbers shown

0: Exit
1: List Products
2: Buy Product
3: Find Product
4: Show Cart
5: Checkout
```

From here, the shopper should be able to select any of the 6 options displayed to them. For this first step, you will
not build any of the functionality associated with options numbered 1-5, and instead will just print text to confirm
their selection.

**For example, if the shopper picks option 1: List Products, the following would be printed to the console:**

`Option 1 was selected. Not yet implemented.`

After any of the options 1 - 5 are selected, and the text has been printed to confirm the shopper's selection, the
application should terminate. Note that this doesn't mean it should print anything extra to the terminal. It just means
the application should close.

You do need to let the shopper know that the application is exiting though, if the shopper selects option 0. When the
shopper selects 0: Exit, they should see the following message and then the application should close:

`Exiting now. Goodbye.`

Here’s what a full set of interactions should look like for this step from the perspective of the shopper when the
shopper enters 0 to exit:

Hello. Please enter your name:
ATA Shopper
Welcome ATA Shopper to T-Shirt Mart

--Main Menu--
Select an option using one of the numbers shown

0: Exit
1: List Products
2: Buy Product
3: Find Product
4: Show Cart
5: Checkout
0
Exiting now. Goodbye.
When any other choice is selected, here's what the shopper should see instead, in this case entering 1 for the menu
selection:

Hello. Please enter your name:
ATA Shopper
Welcome ATA Shopper to T-Shirt Mart

--Main Menu--
Select an option using one of the numbers shown

0: Exit
1: List Products
2: Buy Product
3: Find Product
4: Show Cart
5: Checkout
1
`Option 1 was selected. Not yet implemented.`
