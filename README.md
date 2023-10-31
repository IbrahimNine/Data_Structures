# sumOfDistinctNbrs

## Description:

### Input Sets

   - The algorithm begins by prompting the user to input integers for two separate sets. It employs a procedure called Inputs that reads user input and populates arrays with the provided values.

### Compare and Sum

   - A function named compareAndSum is employed to compare the elements of the two input sets. The function iterates through each element of one set and checks if it is present in the other set. If an element is unique to its set, it is summed to a variable called sum.

### Main Algorithm

   - In the main algorithm sumOfDistinctNbrs, two arrays (firstAr and secondAr) are initialized, and the Inputs procedure is utilized to populate them with user-provided values. Then, the compareAndSum function is called with these arrays to calculate the sum of distinct numbers present in both sets. The final sum is displayed to the user.
   - This algorithm provides a clear and efficient way to find and sum the distinct numbers from two separate sets, making it a useful tool for various applications involving set operations.

# DotProduct

## Description:

### Input Vectors

   - The program prompts the user to input pairs of vectors. For each pair, the user is asked to enter the elements of two vectors. The Inputs procedure reads these values and populates the corresponding arrays.

### Calculate Dot Product

   - A function named Dot_Product is utilized to calculate the dot product of two input vectors. The function multiplies corresponding elements of the vectors and accumulates the results. The dot product represents the degree of similarity or alignment between the two vectors.

### Orthogonality Check

   - Within the DotProduct algorithm, the program reads the number of vector pairs to be processed. For each pair, it calculates the dot product using the Dot_Product function. If the dot product is equal to 0.0, the program declares that the vectors are orthogonal (perpendicular). If the dot product is non-zero, the vectors are deemed non-orthogonal.
