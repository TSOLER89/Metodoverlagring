FormatName Demo

A small C# program demonstrating method overloading with FormatName.

Features

FormatName(string first, string last)
Returns first name + last name.
→ FormatName("Tsoler", "Hayitian") → Tsoler Hayitian

FormatName(string first, string middle, string last)
Returns first name + middle name + last name.
→ FormatName("Tsoler", "Soleya", "Hayitian") → Tsoler Soleya Hayitian

FormatName(string first, string last, bool uppercase)
Returns full name, with an option to make it uppercase.
→ FormatName("Tsoler", "Hayitian", true) → TSOLER HAYITIAN

Example Output
Tsoler Hayitian
Tsoler Soleya Hayitian
TSOLER HAYITIAN
