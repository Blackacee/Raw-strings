# Raw-strings

const patternString = String.raw`Welcome, (\w+)!`;
const pattern = new RegExp(patternString);
const message = "Welcome, John!";
pattern.exec(message);
["Welcome, John!", "John"]
