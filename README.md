## Data Structure

### 1. Arrays

#### Description
- Fixed-size sequential collection of elements of the same type.
- Used when the number of elements is known and fixed.

#### Example
```cpp
#include <iostream>
using namespace std;

int main() {
    int arr[5] = {1, 2, 3, 4, 5};
    for(int i = 0; i < 5; i++) {
        cout << arr[i] << " ";
    }
    return 0;
}

```
### Built-in Functions:
 - None directly; use loops or the algorithm library.
### When to Use:
 - When the size of the collection is fixed and known at compile time.
