# MongoDB $inc operator error: expecting number, found string
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, attempting to increment using a string value results in an error. 

**Bug:** The code incorrectly uses a string value ("1") to increment the `counter` field. This leads to an error because `$inc` expects a numerical value.  

**Solution:** The solution corrects the issue by providing a numerical value (1) to the `$inc` operator. 