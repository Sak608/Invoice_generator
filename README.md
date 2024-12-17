# Invoice Generator WebApp - ReactJs

![React](https://img.shields.io/badge/React-18181b?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)


This project is an Invoice Generator WebApp developed using React and TailwindCSS. The application allows users to add items, specify quantities, input prices, apply tax rates, and include discounts. Users can generate invoices and download them as PDFs, which can then be printed. The project utilizes [html-to-image](https://github.com/bubkoo/html-to-image) to capture data from the modal and convert it from canvas to PDF using [jsPDF](https://github.com/parallax/jsPDF).

### Live Demo

Check out the live demo of the Invoice Generator WebApp [here](https://react-invoice-generator.web.app/).

### Screenshots

Here are some screenshots showcasing the application:

![Screenshot 1](https://imgur.com/rjisRPZ.jpg)
![Screenshot 2](https://imgur.com/vuiKcrK.jpg)
![Screenshot 3](https://imgur.com/bXNiAHT.jpg)

### Tools Used

- **React**: React was used as the main framework for building the user interface. Its component-based architecture facilitated the creation of reusable UI components, enhancing development efficiency and code maintainability.

- **Tailwind CSS**: Tailwind CSS provided utility-first CSS classes, enabling rapid and consistent styling across the application. Its flexibility allowed for easy customization of the user interface to meet the project's design requirements.

- **Headless UI**: Headless UI components were leveraged to create accessible and customizable UI elements without relying on any predefined styles. This ensured that the components seamlessly integrated with Tailwind CSS for a cohesive look and feel.

- **Html-to-image**: This library was essential for capturing the data displayed in modals and converting it into an image. This intermediate step was crucial for generating the PDF invoices.

- **jsPDF**: jsPDF was utilized to take the image generated by html-to-image and convert it into a downloadable PDF file. This library made it possible to generate professional-looking invoices that users could download and print.

### Installation

To set up the project locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/Sak608/Invoice_generator.git
```

3. Navigate into the project directory:
```
cd Invoice-generator-webapp
```

5. Install the required dependencies:
```
npm install
```

7. Start the development server:
```
npm start
```

9. To create a production build, use:
```
npm run build
```

Ensure that you have Node.js and npm installed on your machine before running these commands. Additionally, you may need to configure your environment for React development if not already set up.

### Meta

Created by Sakshi Raj
