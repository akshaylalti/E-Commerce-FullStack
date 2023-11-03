# E-Commerce Full Stack Website

This project is an E-Commerce website built with Angular for the front-end, ASP.NET Core Web API for the back-end, and SQL Server as the database. It is designed to provide a full-fledged online shopping experience, complete with user authentication, product listings, shopping cart functionality, and order processing.

## Features

- **User Authentication**: Users can create accounts, log in, and manage their profiles.

- **Product Listings**: Display a catalog of products with details like images, descriptions, prices, and availability.

- **Shopping Cart**: Users can add and remove products from their shopping cart, view the cart contents, and proceed to checkout.

- **Checkout**: Users can provide shipping information, payment details, and place orders.

- **Order History**: Users can view their order history, including details of past purchases.

- **Admin Panel**: An admin panel for managing products, orders, and user accounts.

- **Search and Filters**: Users can search for products and apply filters to narrow down product listings.

- **Pagination**: Large product listings are paginated for better performance and usability.

## Technologies Used

- **Front-end**: Angular (Angular CLI)
- **Back-end**: ASP.NET Core Web API
- **Database**: SQL Server
- **Authentication**: JWT (JSON Web Tokens)
- **Data Access**: Entity Framework Core
- **Styling**: CSS and Bootstrap
- **Dependency Management**: npm (Node Package Manager)
- **Version Control**: Git

## Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-e-commerce-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-e-commerce-project
   ```

3. Install front-end dependencies:

   ```bash
   cd ClientApp
   npm install
   ```

4. Set up the SQL Server database and update the connection string in the `appsettings.json` file in the API project.

5. Apply database migrations:

   ```bash
   dotnet ef database update
   ```

6. Build and run the API:

   ```bash
   dotnet run
   ```

7. Build and run the Angular front-end:

   ```bash
   cd ClientApp
   ng serve
   ```

8. Access the website in your web browser at `http://localhost:4200/`.

## Screenshots

![E-Commerce Screenshot 1](/screenshots/screenshot1.png)
![E-Commerce Screenshot 2](/screenshots/screenshot2.png)

## Contributing

Contributions to this project are welcome. If you have any suggestions or find issues, please create a GitHub issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

You should adapt this README template to your specific project's details, including the project's structure, file paths, and any specific setup instructions. Additionally, make sure to include the relevant license information and any specific guidelines for contributing to your project.
