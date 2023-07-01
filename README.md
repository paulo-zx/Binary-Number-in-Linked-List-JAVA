# Binary-Number-in-Linked-List-JAVA

You have to complete a function getNumber which receives a single argument H , where H is the head of a linked list. Each node of the linked list contains an integer which is either 1  or 0 . Placing all the integers present in the linked list in a order from left to right, forms a binary number. Return the decimal representation of the binary number to the base 10.

You have to add a function with the following definition

long long getNumber(Node *head) {
    // Complete this function
}
Input Format

First line of input will contain the length of linked list, N.
In second line, there are N space separated integers, where each integer is either 0  or 1. The i^th  value represents the data at the corresponding node.

Output Format

Print the decimal format of integer represented by list.

Constraints

1<= N <= 63

Data at each node will be either 0 or 1
The input can have preceding zeros.
Input/output will be handled by us. Don't print anything in the code.
Sample Input

7
0 0 1 1 0 1 0
Sample Output

26
Explanation

The given linked list is 0->0->1->1->0->1->-> . The binary number formed is 0011010[2] and its decimal representation will be 26[10].

LINK:https://www.hackerrank.com/contests/code-cpp-may-2015/challenges/linked-list-to-binary
