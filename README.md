# Exercise-API
This is a section of the dev project currently in progress. With this repository we intend to get tasks on programming so as to use it as an api for the exercise section of the parent project. This API is available to all, the website link will be posted soon.
___
**Note:** Each tasks will be attributed to an author otherwise specified as anonymous.
___
## Guidelines of Contributing in the Exercise API

This API contains an array of objects called tasks, each objects contains keys and values. To add to this, simply locate the closing braces of the last object, add a comma and create your object.
Below are the following keys your object should contain with each of their possible data types specified.
**Note:** Each tasks will be attributed to an author otherwise specified as anonymous.

1. The **id** key: The _id_ is dependent on the last task's id, so simply increment the last task's _id_ by 1 and use that as your task's _id._ **Data Type:** _Number_.
2. The **task** key: The value of the _task_ key should be your exercise / question / challenge.
   **Note:** It is important to note that the value of this key (i.e the exercise, question or challenge) must involve code writing. I.e to solve your task i should write some lines of code (that's what makes it a task), if it is a _Yes or No_ answer or with options of possible solutions, then it should be taken to the quiz segment of the API. **Data Type:** _String_
3. The **src** key (_optional_): If you choose to let the website display your name as the author of the task, then leave your name here as the value to this key. If the task wasn't generated by you, it is recommended to leave the name of the original author, if the name of that author is unknown, leave value as _anonymous_. **Data type:** _String_.
4. The **srcURL** key (_optional_): Use this key to link the task to it's original source, be it you or someone else. Link can be the author's profile or where the task was posted. It is important to include _https://_ or _http://_ as well as a domain name (.org, .com, .co etc) to this value. If original source has got no link or is unknown, please leave blank. **Data type:** _String_.

#### That's all about making a pull request on this project. Thank you for contributing.
