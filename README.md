# to-implement-matrix-addition
X = [[8, 5, 1],
     [9, 3, 2],
     [4, 6, 3]]

Y = [[8, 5, 3],
     [9, 5, 7],
     [9, 4, 1]]

# Initialize result matrix with zeros
result = [[0, 0, 0],
          [0, 0, 0],
          [0, 0, 0]]

# Add corresponding elements of X and Y
for i in range(len(X)):
    for j in range(len(X[0])):
        result[i][j] = X[i][j] + Y[i][j]

# Print result row by row
for k in result:
    print(k)
    output 
    [16, 10, 4]
[18, 8, 9]
[13, 10, 4]
