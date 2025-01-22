# Invoicera

The **Invoicera** is a Retail Billing System, Python-based desktop application built using `Tkinter` to streamline billing operations for retail stores with a user-friendly interface.

**Customer Details Section**: 
  - Input fields for customer name, phone number, and bill number.
  - Search functionality to retrieve past bills (if implemented).
  
- **Product Categories**: 
  - **Cosmetics**: Includes items like bath soap, face cream, face wash, hair oil, hair gel, and body lotion.
  - **Grocery**: Covers essential items like rice, oil, daal, wheat, sugar, and tea.
  - **Cold Drinks**: Contains beverages such as Maaza, Pepsi, Sprite, Mountain Dew, Frooti, and Coca-Cola.
  
- **Bill Menu**: 
  - Input fields for total price and tax for each product category.
  
- **Bill Area**: 
  - Displays the generated bill in a clear and readable format.

- **Functional Buttons**: 
  - **Total**: Calculates the total amount, including taxes.
  - **Bill**: Generates the bill details in the text area.
  - **Email**: Sends the bill via email (if configured).
  - **Print**: Provides a print option for the bill.
  - **Clear**: Resets all fields for a new transaction.

- **Customization Options**: 
  - Easy to add or modify products based on business requirements.
  - Built-in random bill number generation for unique identification.

- **Backend Functionalities**: 
  - Uses Python libraries such as `random`, `os`, `tempfile`, and `smtplib` for file handling and email functionality.

## Requirements

To run the Retail Billing System, you will need the following dependencies installed:

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- Other dependencies are listed in the `requirements.txt` file.


---

## Installation

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/retail-billing-system.git
   cd retail-billing-system
   
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the application:
   ```bash
   python main.py
   
## Building the Executable
To create an executable for the system using `cx_Freeze`, follow these steps:
- 1. Build the executable:
     ```bash
     python setup.py build
     
- 2. To create an MSI installer:
     ```bash
     python setup.py bdist_msi


## How to Use
- **Input customer details and product quantities.**
- **Click Total to calculate amounts with taxes.**
- **Use Bill to generate an invoice, Email to send it, or Print to print it.**
- **Clear resets the fields for new transactions.**

## Future Enhancements
- **Database integration for storing invoices.**
- **Advanced search functionality.**
- **Modern UI design.**
- **Multi-user support with login credentials.**

## Screenshot
