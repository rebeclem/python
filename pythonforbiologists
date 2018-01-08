  https://pythonforbiologists.com/
  
  # how to include a newline in the middle of a string
print("Hello\nworld")
--
# this line doesn't produce any output
len("ATGC")
# store the DNA sequence in a variable
my_dna = "ATGCGAGT"

# calculate the length of the sequence and store it in a variable
dna_length = len(my_dna)

# print a message telling us the DNA sequence lenth. You have to make dna_length a string.
print("The length of the DNA sequence is " + str(dna_length))
--
With lower() and upper(), you have to save it as something else.
my_dna = "ATGC"

# print the variable
print("before: " + my_dna)

# run the lower method and store the result
lowercase_dna = my_dna.lower()

# print the variable again
print("after: " + lowercase_dna)
--
protein = "vlspadktnv"

# replace valine with tyrosine
print(protein.replace("v", "y"))

# we can replace more than one character
print(protein.replace("vls", "ymt"))
--
printing substrings:
protein = "vlspadktnv"

# print positions three to five
print(protein[3:5])

# positions start at zero, not one
print(protein[0:6])

# if we miss out the last number, it goes to the end of the string
print(protein[2:])
--
Counting things
protein = "vlspadktnv"
# count amino acid residues
valine_count = protein.count('v')
lsp_count = protein.count('lsp')
tryptophan_count = protein.count('w')

# now print the counts
print("valines: " + str(valine_count))
print("lsp: " + str(lsp_count))
print("tryptophans: " + str(tryptophan_count))
--
find will give you the index number
protein = "vlspadktnv" 
print(str(protein.find('p'))) 
print(str(protein.find('kt'))) 
print(str(protein.find('w'))) # you get -1 if it doesn't exist in the string
