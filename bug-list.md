# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

Not fixed:


Fixed:

1. Problem: The if and else if elements don't recognise words that are being input. It had to do with the fact I had .toLowerCase with uppercase letters.
2. Problem: The script end tag says unexpected end of input in console. Accidentally deleted a curly bracket when coding, fixed by adding it.
3. Problem: You get 8x more health potions than what you bought at the merchant. Fixed by dividing the variable used by 8.
4. Problem: Any answer to which health potion to use always resulted in a big health potion being consumed. Fixed by adding heal.toLowerCase to every condition.
