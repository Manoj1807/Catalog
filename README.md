Output:

This code will print the reconstructed secret (constant term c) based on the provided JSON data.

If c can be simplified to an integer (denominator = 1), it will print the numerator.
If c is a fraction, it will print the entire rational representation (numerator/denominator).
Example Output:

Reconstructed secret (integer): 12345
Reconstructed secret (fraction): 1/2
Improvements:

Error Handling: Consider adding more robust error handling for invalid JSON data formats or missing keys.
Flexibility: The code assumes a specific JSON structure. You could enhance it to handle variations in how shares are stored.
Comments: Adding more comments within the code would improve readability and understanding.
