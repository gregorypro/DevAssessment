# DevAssessment

# 1) Binary Search

Problem
Implement a standard binary search algorithm.

Constraints
None.  Any language

Examples
func BinarySearch(source []int, value int) int { }

func main() {
	values := []int{1, 2, 3, 4, 5, 6, 7}
	fmt.Println(BinarySearch(values, 5))
}
Input: []int{1, 2, 3, 4, 5, 6, 7}, 5
Output: 4

---------------------------------------------------------------------------

# 2) Target Value
Given two arrays a and b and target value t, write a function that returns the two values from each array that add up to the target t.

Ex:

const a = [3, 5, 7, 8]
const b = [3, 5, 1, 9]
const t = 12

const result = findTarget(a, b , t) // returns [[3, 9], [7, 5]]
Constrains:

assume arrays always have same length
values of arrays are int >= 0
t = int >=0
if no match return []

---------------------------------------------------------------------------------------------------------------------


