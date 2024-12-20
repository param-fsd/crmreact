# Importing And Exporting Data

## Importing Data

You can import contacts and companies from a CSV file, e.g. to migrate from another CRM.

https://github.com/user-attachments/assets/278a1969-b67f-4128-b75f-23e1b6ac1090

Atomic CRM displays an import contact buttons in the initial user onboarding page, and in the contacts page. 

An example of the expected CSV file is available in the contact import modal:

```csv
first_name,last_name,gender,title,company,email,phone_1_number,phone_1_type,phone_2_number,phone_2_type,background,first_seen,last_seen,has_newsletter,status,tags,linkedin_url
John,Doe,male,Sales Executive,Acme,john@doe.example,659-980-2015,work,740.645.3807,home,,2024-07-01,2024-07-01T11:54:49.950Z,FALSE,in-contract,"influencer, developer",https://www.linkedin.com/in/johndoe
Jane,Doe,female,Designer,Acme,jane@doe.example,659-980-2020,work,740.647.3802,home,,2024-07-01,2024-07-01T11:54:49.950Z,FALSE,in-contract,"UI, design",https://www.linkedin.com/in/janedoe
Camille,Brown,nonbinary,Accountant,Atomic Corp,person@doe.example,659-910-3010,work,740.698.3752,home,,2024-07-01,2024-07-01T11:54:49.950Z,FALSE,in-contract,"payroll, accountant",,
```

When importing contacts, companies and tags will be automatically matched if they exist on the system, or imported ortherwise.

## Exporting Data

In the contacts and companies pages, an export button allows to download the list of contacts or companies in CSV format.
