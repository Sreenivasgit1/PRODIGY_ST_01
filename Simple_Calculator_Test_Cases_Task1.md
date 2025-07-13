
# 🧮 Simple Calculator Test Cases

## ✅ Positive Test Cases

| **Test Case ID** | **Test Description**                      | **Preconditions**        | **Test Steps**                                                                                                                                   | **Expected Result**                     |
|------------------|-------------------------------------------|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
| TC_ADD_01        | Addition of two positive numbers          | Calculator is running     | 1. Enter `5`<br>2. Press `+`<br>3. Enter `3`<br>4. Press `=`                                                                                      | Display shows `8`                        |
| TC_ADD_02        | Addition of positive and negative numbers | Calculator is running     | 1. Enter `7`<br>2. Press `+`<br>3. Enter `-4`<br>4. Press `=`                                                                                     | Display shows `3`                        |
| TC_SUB_01        | Subtraction with positive result          | Calculator is running     | 1. Enter `9`<br>2. Press `-`<br>3. Enter `4`<br>4. Press `=`                                                                                      | Display shows `5`                        |
| TC_SUB_02        | Subtraction with negative result          | Calculator is running     | 1. Enter `2`<br>2. Press `-`<br>3. Enter `5`<br>4. Press `=`                                                                                      | Display shows `-3`                       |
| TC_MUL_01        | Multiplication of two numbers             | Calculator is running     | 1. Enter `6`<br>2. Press `*`<br>3. Enter `7`<br>4. Press `=`                                                                                      | Display shows `42`                       |
| TC_MUL_02        | Multiplication with zero                  | Calculator is running     | 1. Enter `0`<br>2. Press `*`<br>3. Enter `999`<br>4. Press `=`                                                                                    | Display shows `0`                        |
| TC_DIV_01        | Division with whole number result         | Calculator is running     | 1. Enter `10`<br>2. Press `/`<br>3. Enter `2`<br>4. Press `=`                                                                                    | Display shows `5`                        |
| TC_DIV_02        | Division with decimal result              | Calculator is running     | 1. Enter `7`<br>2. Press `/`<br>3. Enter `2`<br>4. Press `=`                                                                                      | Display shows `3.5`                      |

## ❌ Negative Test Cases

| **Test Case ID** | **Test Description**               | **Preconditions**         | **Test Steps**                                                                                                                     | **Expected Result**                              |
|------------------|------------------------------------|----------------------------|------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| TC_DIV_03        | Division by zero                   | Calculator is running      | 1. Enter `5`<br>2. Press `/`<br>3. Enter `0`<br>4. Press `=`                                                                       | Display shows `Error` or `Cannot divide by zero` |
| TC_ERR_01        | Invalid (non-numeric) input         | Calculator allows text     | 1. Enter `"abc"`<br>2. Press `+`<br>3. Enter `5`<br>4. Press `=`                                                                  | Display shows `Error` or ignores input           |
| TC_ERR_02        | Missing operator                    | Calculator is running      | 1. Enter `8`<br>2. Press `=`                                                                                                       | Display shows `8` or `Incomplete Expression`     |
