presscreen.html contains a textarea, a button for Key/Value Totals and a Clear button to clear the text area and output.

Each line in the textarea should contain a key, separated from count by a ':' character. The key may be any string without a colon. The count is expected to be able to be parsed to an integer.

Default input: 
               John: 2
               Jane: 3
               John: 4
               Jane: 5

Output for the default input: Sums the counts for each key (case insensitive) in the textarea, and displays the totals for each key
                             
                             The total for john is 6.

                             The total for jane is 8.

If the key entered in the keycount textarea happens to be a palindrome (case insensitive), like "Bob", "Hannah", or "Ah, Satan sees Natasha!", the output displays "prescreen-palindrome" corresponding to the palindrome Key. 

Example input:  
              John:2
              Jane:3
              John:4
              Jane:5
              Bob:1
              Hannah:6
              bob:4
              hannah:5
              Ah, Satan sees Natasha!:3
              john:2

Output:  
        The total for john is 8.
        The total for jane is 8.
        The total for bob(prescreen-palindrome) is 5.
        The total for hannah(prescreen-palindrome) is 11.
        The total for ahsatanseesnatasha(prescreen-palindrome) is 3.