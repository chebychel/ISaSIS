#ISaSIS
you don't need to explain if you're here. And also, the script is created from Inner Self and Stackable Inventory System & Wallet, and it was compiled by Cardoril (sorry, I don't know your GitHub username). 

To add a script, click on the EDIT SCRIPTS button, then add the input.txt file to input, output.txt to output, context.txt to context, library.txt to library, and click on the save button.
 
/take [itemName]
or
/take [amount] [itemName]
Example: /take 2 Health Potion
How it appears: You take Health Potion x 2 and put them in your inventory.

/collect [amount] [currencyName]
Example: /collect 100 gold coins
How it appears: You collected 100 gold coins.
Note: Only for adding currency to your wallet, not to your inventory.

/use [itemName] to [action]
or
/use [itemName] on [target]
Example: /use Health Potion on Elara
How it appears: You use Health Potion on Elara.
Note: Only use this command if the item is consumable.

/give [amount] [itemName] to [target]
Example: /give 2 Toy Car to the child
How it appears: You give 2 Toy Car to the child.
Note: Also works with wallet currencies.

/throw [itemName] at [target]
Example: /throw Rock at Elara
How it appears: You throw Rock at Elara.
Note: Can only throw one item at a time.

/drop [amount] [itemName] on [location (optional)]
Example: /drop 2 Iron Bar
Reply: You drop 2 Iron Bar on the forge.
Note: You can leave the amount empty to drop just one item.

Custom Commands

You can define custom commands in the Custom Commands card.

Custom Command Format:
    Name: /example (the name of your command, with a slash in front)
    Type: add or remove (does this command add or remove items?)
    Multiples: true or false (does this command accept multiple items, or does it only apply to one item?)

You can have multiple custom commands within the card; just copy and paste the format for each command.
