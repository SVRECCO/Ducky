# Ducky Ordering System

This is a C# program developed by TechStarWebDesign that allows users to order rubber duckies using the Stripe API. The program is designed to be run on the command line or in a console window.
Requirements

    .NET Core 3.1 or higher
    Stripe API credentials (test or live)

Installation

To install the Rubber Duckie Ordering System, follow these steps:

    Clone the GitHub repository or download the source code.
    Navigate to the project directory in a terminal or command prompt.
    Run dotnet build to build the project.
    Create a file named appsettings.json in the project directory with the following content:

json

{
  "Stripe": {
    "ApiKey": "YOUR_STRIPE_API_KEY"
  }
}

Replace YOUR_STRIPE_API_KEY with your actual Stripe API key.
Usage

To use the Rubber Duckie Ordering System, follow these steps:

    Run the program by executing the command dotnet run in the project directory.
    Follow the on-screen prompts to enter your shipping address, credit card information, and order details.
    Once all required information has been entered, the program will charge your credit card and display a confirmation message.

Note: The program is currently set up to only accept orders for rubber duckies, but it could be modified to accept orders for other products as well.
Credits

The Rubber Duckie Ordering System was developed by TechStarWebDesign, with assistance from the Stripe API documentation and community. If you have any questions or issues with the program, please contact us at support@techstarwebdesign.com.
License

The Rubber Duckie Ordering System is licensed under the MIT License. See LICENSE.txt for more information.
