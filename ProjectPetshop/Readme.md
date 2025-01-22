```markdown
# Petshop Management Application

A comprehensive desktop application built with Python and Tkinter for managing pet shop operations. This project includes features for customer registration, product sales, service bookings, and automated email notifications.

## Features

- **User Authentication**: Secure login and registration system with OTP and PIN setup.
- **Product Management**: Manage pet products and equipment, including purchase summaries and transaction history.
- **Service Booking**: Schedule and manage grooming services with real-time validation.
- **Email Notifications**: Automated email confirmations for transactions and service bookings.
- **PDF Reports**: Generate detailed transaction reports in PDF format.
- **Responsive UI**: Intuitive and user-friendly interface designed with Tkinter.

## Project Structure

```
project/
├── Petshop_App.py       # Main application file
├── shortcut_pandas.py   # Helper functions for email and data operations
├── data/                # Directory containing CSV data files
│   ├── login.csv        # User login data
│   ├── Daftar_Produk.csv # List of products
│   ├── Daftar_Peralatan.csv # List of equipment
│   └── data_transaksi.csv # Transaction history
├── image/               # Directory containing UI assets
│   ├── image_1.png      # Login page background
│   ├── image_2.png      # Register page background
│   ├── button_a.png     # Back button
│   ├── pawpaw.png       # Logo
│   └── ...              # Other image assets
```\

## Requirements

- Python 3.9 or higher
- Required Python packages:
  - `tkinter`
  - `pandas`
  - `fpdf`
  - `tkcalendar`
  - `smtplib`
- Additional assets:
  - Images in the `image/` directory
  - CSV files in the `data/` directory

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/petshop-app.git
   cd petshop-app
   ```

2. Install dependencies:
   ```bash
   pip install pandas fpdf tkcalendar
   ```

3. Run the application:
   ```bash
   python Petshop_App.py
   ```

## Usage

1. **Login/Register**: Start with user authentication.
2. **Product Management**: Navigate to the product menu for purchases.
3. **Service Booking**: Schedule grooming services via the service menu.
4. **Reports**: Access transaction history and generate PDF reports.
5. **Email Notifications**: Ensure the email server configuration is correct in `shortcut_pandas.py`.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries, please contact [Alyssachalondra@gmail.com].
```
Let me know if you'd like any changes!