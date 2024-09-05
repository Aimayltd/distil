
# Flutter Airtable-like Table

A fully customizable Flutter widget replicating the functionality and user experience of Airtable-like tables. This widget allows developers to integrate a flexible table into their applications, supporting various data types and features. The table is ideal for creating applications that require real-time data entry, dynamic column types, and task management with subtask support.

## Features

### Column Types
This table interface supports the following column types:

- **Single Line Text**  
  Allows users to input short strings of text.

- **Multiple Line Text**  
  Allows users to input longer strings of text, supporting line breaks.

- **Numeric**  
  For entering numerical values with options for calculations and formatting.

- **Single Select**  
  A dropdown list that lets users select one option from a predefined list.

- **Multiple Select**  
  A multi-select dropdown where users can choose several options from a predefined list.

- **Date**  
  Allows users to select a date from a date picker.

- **Rating**  
  Provides users with a star or numerical rating system to rate items.

- **Checkbox**  
  A simple boolean input represented by a checkbox (checked/unchecked).

- **Formula**  
  Supports formulas for calculating values based on other fields.

- **Link**  
  Stores valid URL links, with clickable support to open in a browser.

- **Lookup**  
  Looks up data from another table or row, making it possible to display related information.

- **Rollup**  
  Aggregates data from linked records in another table (such as SUM, AVG, MIN, MAX).

- **User**  
  Assigns users from a predefined list of people (useful for task assignment).

- **Created By**  
  Automatically stores the user who created the record.

- **Created Time**  
  Automatically stores the time when the record was created.

- **Last Modified By**  
  Automatically stores the user who last modified the record.

- **Last Modified Time**  
  Automatically stores the time when the record was last modified.

- **Auto Number**  
  Automatically generates a unique number for each new record, starting from 1.

- **Attachment**  
  Supports file attachments, allowing users to upload and manage multiple files within the cell.

- **Subtask Column**  
  A specialized column for managing tasks and subtasks. 

- **Comment**  
  A column where users can leave and manage comments. Useful for adding context or notes to a specific record or task.

- **Geolocation**  
  Stores latitude and longitude coordinates, useful for mapping or location-based data.

- **Barcode/QR Code**  
  Allows for storing and generating barcodes or QR codes.

- **Button**  
  Customizable buttons for triggering actions like opening links, running scripts, or triggering workflows.

### Additional Features
- **Dynamic Columns and Rows**: Easily add and remove columns and rows based on user input.
- **Sorting and Filtering**: Each column supports sorting and filtering for better data management.
- **Mobile Responsiveness**: Optimized for mobile and web applications, offering a seamless user experience across devices.
