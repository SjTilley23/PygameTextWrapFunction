This is a function that uses pygame to render and display a string that automatically wraps to a new line when needed

renderTextWrap(text, font, color, allowedWidth, window, x, y, shiftInY)

text - "This is your string, in quotations like this"

font - Variable you assigned your font to,  
ex: if you had ...     Type = pygame.font.Sys_font("Tahoma", 72)
you would put   "Type"  without the quotations, for the font argument

color - color you want the text to be. has to be a tuple like this   (0,0,0)
	parentheses must be included

allowedWidth - this is the allowed width of the text in pixels

window - where you want to display the text

x - x coordinate of the top left of the first letter

y - y coordinate of the top left of the first letter

shiftInY - This how far down you want a new line to be placed from the previous in pixels