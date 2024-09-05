# AO Dataset Sample specification


## Overview

Welcome to the AO AI Assistant - Dataset Competition Pool! This competition invites participants to contribute datasets related to AO, facilitating the development of an intelligent AI assistant that enhances user interaction with the platform. This README provides guidelines for the format and structure of dataset submissions.


## Data Sample Format

Below is a sample of the data format for the competition. Each entry should follow this structure:

```json
[
  {
    "content": "Question: What is the AO computer? Answer: The AO computer is a decentralized computing system inspired by the actor-oriented paradigm, capable of supporting numerous parallel processes without the constraints typical of current decentralized computation models.",
    "meta": {
      "time": "2021-02-15 07:16:15"
    }
  },
  {
    "content": "Question: how much $DAI has been deposited to AO!? Answer: 15 million $DAI has been deposited to AO!",
    "meta": {
      "time": "2021-02-14 08:24:28"
    }
  }
]
```

### Data Fields

- **content**: This field contains a question and answer pair related to AO. It should be written in a clear and concise manner.
- **meta** (optional): This field contains metadata about the entry. The metadata can include various attributes, but in this example, it includes a timestamp indicating when the entry was created.

### Metadata Fields

- **time**: A timestamp indicating when the entry was created, formatted as "YYYY-MM-DD HH:MM:SS".

## Submission Guidelines
Participants should submit their datasets in JSON format following the sample structure provided above. Ensure that each entry is relevant and accurately represents information about AO and its functionalities.

### How to Submit

1. Prepare your dataset in JSON format.
2. Include both required and optional fields as specified.
3. Upload your dataset to Apus Network

## Evaluation Criteria

Datasets will be evaluated based on the following criteria:

- **Relevance**: The information provided should be pertinent to AO and its ecosystem.
- **Accuracy**: Ensure that all entries are factually correct.
- **Completeness**: While the meta field is optional, including it will add value to the dataset.
- **Format Compliance**: Submissions must adhere to the provided JSON structure.

## Additional Information

For more details and updates on the competition, please visit the [Apus Network website](https://apus.network/). If you have any questions or need further assistance, feel free to reach out to our support team.

We look forward to your participation and wish you the best of luck in contributing to the AO AI Assistant - Dataset Competition Pool!
