## Unsupervised Learning

- We are given data that has no labels, or the same labels. We are not given a dependant variable.
- We are given a data set but not told what to do with it
- For example, clustering algorithms. Clusters related data together

## Cocktail Party Algorithm

- Suppose two people are speaking together, their voices are overlapping each other. We have an algorithm that can decipher both voices seperately.
- Equation is: [W, s, v] = svd((repmat(sum(x.*x,1), size(x, 1), 1).*x)*x')

