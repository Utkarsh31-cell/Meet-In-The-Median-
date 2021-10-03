Link to problem : https://www.codechef.com/problems/SUBMEDIA

Question explaination: In this problem basically what we have given in question is n,k and array of length n.
We have to find the highest median containing a k length array, i.e. an array of length k and containing median which is highest value among all k length array made from given array of length n such that array are taken as subsequnce way.

Question :
You're given a sequence of N distinct integers. You need to find a subsequence of length K with the maximum possible median.

The median of a sequence is the value of the element which is in the middle of the sequence after sorting it in non-decreasing order. If the length of the sequence is even, the left of two middle elements is selected. For example, if the sequence is [3,4,2,1,5], then the median is 3 since after sorting, it will look like [1,2,3,4,5] and 3 is the only middle element. The median of [4,2,1,5] is 2 since after sorting, the value 2 is the left of the two middle elements 2 and 4.

A subsequence is a sequence that can be derived from the given sequence by deleting zero or more elements without changing the order of the remaining elements. For example, if the sequence is [2,1,4,5,7], then [1,5,7], [2,1,4], [5] are some valid subsequences but [4,1,2], [1,6,7] are not.

1≤T≤30
1≤K≤N≤2×105
1≤Ai≤109
Sum of N over all test cases won't exceed 5×105
Test cases:
input :
2
5 3
1 4 3 6 5
5 4
1 4 3 6 5
output:
5
4 6 5 
4
4 3 6 5
Link for understanding median array concepts: https://discuss.codechef.com/t/submedia-editorial/94185
                   
