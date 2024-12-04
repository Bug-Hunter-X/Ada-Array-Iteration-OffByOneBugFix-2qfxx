This repository demonstrates a common off-by-one error in Ada when iterating through arrays. The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides the corrected version. The error arises from incorrectly assuming that loop iterators start from 0 instead of the array's lower bound (which is usually 1 in Ada). The solution ensures proper indexing, highlighting best practices for array traversal in Ada.