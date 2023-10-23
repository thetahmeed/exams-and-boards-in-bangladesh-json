# Exams and Boards in Bangladesh

This repository provides a JSON containing a list of exam options. The data is organized to include exam labels, values, and numerical IDs. You can use this data in your projects as a reference or for any other purpose.

## JSON Data Structure

The JSON-like data structure is organized as follows:

```json
{
  "exam_options": [
    {
      "id": 1,
      "value": "ssc",
      "label": "SSC/Dakhil/Equivalent"
    },
    {
      "id": 2,
      "value": "jsc",
      "label": "JSC/JDC"
    },
    // ... (other exam options)
  ]
}
```
Each exam option is represented as an object with a unique numerical ID, value, and label describing the exam type.
# Usage
You are free to use this data in your projects under the terms of the open-source license. To use the data, you can clone or download this repository and then access the `exams-in-bangladesh.json` file for the data.
# Example Usage
Here's an example of how to access the data using JavaScript:
```
// Load the file
const examList = require('./exams-in-bangladesh.json');

// Access exam options
examList.exams.forEach(option => {
  console.log(`ID: ${option.id}, Value: ${option.value}, Label: ${option.label}`);
});
```
# Contributing
If you have additional exam options to add or any improvements to suggest, please feel free to contribute to this repository. You can create a pull request with your changes.

# License
This project is open-source and available under the Apache License 2.0. Please review the license file for detailed terms and conditions.

# Acknowledgments

# By
Tahmeedul Islam
