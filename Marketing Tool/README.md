# Key Points

- The app for SMS/MMS bulk messaging allows sending messages, viewing received SMS, creating surveys/campaigns with conditional flows, and validating numbers using NumVerify and Twilio APIs.
- Both apps are built using Python and PyQt5, with the SMS/MMS app additionally using NumVerify and Twilio APIs for number validation and messaging.

![Alt](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Marketing%20Tool/login.png "Login")

## Project Overview

The SMS/MMS Bulk Messaging App is a desktop application designed to streamline mass communication for businesses or individuals. It enables users to send SMS and MMS messages in bulk, view received SMS, create surveys or campaigns with conditional question flows, and validate phone numbers using NumVerify and Twilio APIs. Built with a user-friendly interface, this app provides a comprehensive solution for managing marketing campaigns, customer engagement, and communication workflows, ensuring efficiency and accuracy in messaging.

## Features

- **Bulk SMS/MMS Sending**: Screenshot id:8 showed a "MMS" tab with a message input field, a file path input for a list of numbers, a "Browse" button, carrier selection (Twilio, NumVerify), and "Start Messaging" and "Stop Messaging" buttons. This allows users to send messages to multiple numbers efficiently, with control over the process.

![Alt](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Marketing%20Tool/sms.png "SMS")

- **Received SMS Viewing**: Screenshot id:9 displayed a "Chats" tab with a list of numbers (e.g., 17098918360, 15188172137), suggesting users can select a number to view conversation history. This aligns with typical messaging apps, providing a way to manage responses.

![Alt](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Marketing%20Tool/rec.png "Received")

- **Surveys/Campaigns**: Screenshot id:10 showed a "Survey" tab with a table listing questions, answers, and navigation buttons ("Answer," "Next"). This allows users to create campaigns with multiple questions and define flows based on responses, enabling conditional logic (e.g., if answer A, go to question 2; if answer B, go to question 3).

![Alt](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Marketing%20Tool/survey.png "Survey")

- **Number Validation**: Screenshot id:8 included carrier options (Twilio, NumVerify), and id:9 showed a "Validation" tab, indicating bulk number validation. The user mentioned using NumVerify and Twilio APIs, which validate phone numbers for accuracy and carrier details, ensuring effective messaging.

![Alt](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Marketing%20Tool/validation.png "Validation")

## Tech Stack

| **Technology** | **Description**                                                                 |
|----------------|---------------------------------------------------------------------------------|
| Python         | Used for core development, handling login logic and user authentication, and API integration. |
| PyQt5          | A Python library for building the graphical user interface, supporting tabs and widgets for messaging, surveys, and validation. |
| NumVerify API  | Used for phone number validation, checking number validity and carrier details ([NumVerify API](https://numverify.com/)). |
| Twilio API     | Used for sending SMS/MMS, managing communication, and validating numbers ([Twilio API](https://www.twilio.com/docs)). |
