# Expenses_tracks
adulting - just starting to be more conscientious about my own spendings (personal use)
every online expense trackers are often missing one or two functions, or customizable options - have decided to make my own
# intended use
a series of VBA codes that imports and compiles monthly credit card spendings into various pre-defined categories
currently - it only works for UOB credit card transactions (since it is the bank that i use; identifiers from different banks need to be add in later)
# how it works
## reference to: Import, Keys, and Record tabs
"Import One CC" - this script will select and import the month's CC transactions
"Assign Category" - this script will reference unique strings in the vendors in the "Keys" tab, and auto-assign categories
"Add new keywords or categories" - this script will populate a user_form to assign new vendors or transactions into the "Keys" tab, each to be associated with categories. For instance, {"ASOS": Entertainment}
"Add to Record" - this will add transactions into the master record tab
## reference to Breakdown tab
fill in the cell that requests for "months ago", and "breakdown" will tabulate transactions from that month
"add to compile" - will populate the complete amount based on categories
"clear compile" - is as self-explainatory; to clear the rows from I to Q

### rooms for improvements
- needs to be more automated
- with more transactional data, more vendors will be added
- add more visualization charts: for instance, amount spent on each category
- consider building it in python or another program
- remove or hide sensitive information like specific transaction numbers (if sharing online)
