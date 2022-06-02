# Total Cost

A plugin for [RuneLite](https://github.com/runelite/runelite) which calculates the approximate total cost of an item for various purchase quantites.


## Features
- When Value _"item"_ is selected while viewing an NPC store, chat messages will be added that display the total cost for various purchase quantites.

## Example
![image](https://user-images.githubusercontent.com/14336807/171683717-12b8c84a-ad4f-4af1-b8cd-2be7a28825a7.png)

## Configuration Options
- **Buy 10 cost:** Enables message stating the total cost when purchasing 10 of an item.
- **Buy 50 cost:** Enables message stating the total cost when purchasing 50 of an item.
- **Buy all cost:** Enables message stating the total cost when purchasing all of an item.
- **Highlight Color:** Changes the color that particular parts of the chat message will be colored.

## Notes
- The total cost for all quantites is approximate and cannot be calculated perfectly due to rounding errors. It's usually pretty close, though.

## Version history
- v1.1
  - Added new string to contextualize the amount in stock
  - Added option to display average price
- v1.0
  - Initial release
