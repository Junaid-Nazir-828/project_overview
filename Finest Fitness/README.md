# Project Overview: Finest Fitness Contract Generator

The Finest Fitness Contract Generator is a desktop application designed for a gym to streamline the process of onboarding new members by generating personalized contracts. It allows gym staff to select a membership plan, calculate the total price based on the chosen plan and additional services, and generate a contract that includes the member’s personal information and selected gym plan. Built with a user-friendly interface, this app simplifies membership management, ensuring accurate pricing and efficient contract creation for Finest Fitness.

## Features

- **Membership Plan Selection**: The app offers three pricing tiers—Basic (139€), Premium (189€), and Exklusiv (299€)—each with varying services such as membership activation, entry gloves, water bottles, shakers, sports medicine checkups, body analysis, equipment introduction, EGYM and Flexx training, individual training plans, nutrition coaching, and nutrition counseling. Users can select a plan and additional services (e.g., EGYM Zirkel, Cardio+, Solarium) to customize the membership package.  

  ![Membership Plans](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Finest%20Fitness/plans.png "Membership Plans")

- **Customizable Service Selection**: Users can choose additional services under "Basic-Tarif," "EGYM-Paket," and "Gesund-Paket," such as Zirkel (1.89€), Stand Alone (1.89€), Cardio+ (1.29€), MediStream (3.79€), and more, with prices displayed for transparency. Options for contract duration (9, 12, or 24 months) and a weekly fee (14.98€) are also available, allowing for flexible pricing calculations.

- **Price Calculation**: The app calculates the total price based on the selected plan, additional services, and contract duration. For example, selecting the Premium plan (189€) with EGYM Zirkel (4.49€) and a 12-month contract would compute the final cost, ensuring accurate billing for the gym and transparency for the member.

- **Personal Information Input**: The app includes a form for entering personal details such as gender (Herr/Frau), first name, last name, date of birth, phone number, address (street, postal code, city), email, and payment details (SEPA mandate with account holder and IBAN). A start date for the membership is also specified, ensuring all necessary information is captured for the contract.
  
  ![Personal Information](https://github.com/Junaid-Nazir-828/project_overview/blob/main/public/Finest%20Fitness/personal_info.png "Personal Information")

- **Contract Generation**: Once the plan and personal details are entered, the app generates a contract that includes the member’s information, selected gym plan, additional services, and total price. A button labeled "Abschluss" (Conclusion) finalizes the process, with an option to print the contract, streamlining the onboarding process for gym staff.

### Tech Stack

| **Technology** | **Description**                                                                 |
|----------------|---------------------------------------------------------------------------------|
| Python         | Used for core development, handling logic for price calculation and contract generation. |
| PyQt5          | A Python library for building the graphical user interface, supporting forms, buttons, and selection widgets for plan customization and data input. |
