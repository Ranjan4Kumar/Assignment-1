''' Q1:- Given an array "points" of numbers, a score can be calculated for a subarray [i....j] by..
score = min(points[i....j])*sum(points[i...j]) return the sum of all scores of all possible subarrays
For exampl, points = [2,1,3] in the form index pair = score
0,0 = 4
0,1 = 3
0,2= 6
1,1 = 1
1,2 = 4
2,2 = 9
total = 27
expected Time soltuion: 0(n)'''
