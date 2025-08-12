#include <stdio.h>

int main() {
    int arr[] = {12, 45, 67, 23, 89, 34};
    int n = sizeof(arr) / sizeof(arr[0]);
    int largest = arr[0];

    for (int i = 1; i < n; i++) {
        if (arr[i] > largest) {
            largest = arr[i];
        }
    }

    printf("Largest element: %d\n", largest);
    return 0;
}
PYTHON
# Input array
arr = [12, 45, 67, 23, 89, 34]

# Assume first element is the largest
largest = arr[0]

# Compare with each element
for num in arr:
    if num > largest:
        largest = num

print("Largest element:", largest)

# Find-largest-element-in-array
