# CodeBook

## Data Description
The dataset contains accelerometer and gyroscope measurements from Samsung Galaxy S smartphones worn by participants during activities.

## Variables
Each observation includes:
- `subject`: ID of the subject who performed the activity
- `activity`: Activity name (e.g., WALKING, SITTING)
- Remaining columns: Mean or standard deviation of various sensor measurements

All variables are numeric. The variables represent the average of each original feature for each subject-activity pair.

## Transformations
The following transformations were applied:
- Combined training and test datasets
- Selected only measurements on the mean and standard deviation
- Replaced activity codes with descriptive names
- Cleaned up column names to be more readable
- Created a second tidy dataset containing the average of each variable for each activity and subject
