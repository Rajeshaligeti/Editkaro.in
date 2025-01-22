
# Editkaro.in Website

This is the official website for **Editkaro.in**, a digital editing and marketing agency. The website features several key pages showcasing the services, pricing, portfolio, and more. The project also includes a "Get in Touch" form with email functionality integrated with **Google Sheets** for data storage.

### Live Website
You can view the live website here: [Editkaro.in](https://web-project-xnt2.onrender.com/)

### Demo Video
![Demo Video Thumbnail](thumbnail_image.jpg) 

Watch the demo video to see how the website works and the features it offers:  
[Watch the demo video]([https://drive.google.com/your_video_link](https://drive.google.com/file/d/1FXLSFXCd38FyyCEeg2UzZr5KYNPa-ass/view?usp=sharing))  

*Or*  

[Download the demo video]([https://drive.google.com/your_video_link](https://drive.google.com/file/d/1FXLSFXCd38FyyCEeg2UzZr5KYNPa-ass/view?usp=sharing))  

## Key Features

- **New Web Pages**:
  - **Pricing Page**: Displays 3 service packages with pricing details.
  - **Press and Media Page**: Showcases past events, achievements, and awards.
  - **Services & FAQ Page**: Lists the services provided and answers to frequently asked questions.
  - **Portfolio Page**: Displays client works, including video thumbnails for easy navigation.
  
- **Mail Functionality**:
  - Integrated **Nodemailer** to send automated emails with PDF attachments upon form submission.

- **Data Storage**:
  - Form submissions from the "Get in Touch" form are stored in **Google Sheets** using the **Google Sheets API**.

- **Responsive Design**:
  - The website is designed to be fully responsive using CSS animations and media queries.

## Installation

### Prerequisites

- **Node.js**: Ensure you have **Node.js** and **npm** installed on your system.
- **Google API Key**: You need a Google API key to access the Google Sheets API.

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/editkaro-in.git
   cd editkaro-in
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file and add the necessary environment variables for the **Google Sheets API** and **Nodemailer** configuration.

   Example:

   ```env
   GOOGLE_SHEET_API_KEY=your_google_api_key
   GMAIL_USER=your_email@gmail.com
   GMAIL_PASS=your_email_password
   ```

4. Run the server:

   ```bash
   npm start
   ```

5. Access the website at `http://localhost:3000`.

## Project Structure

```
.
├── public/              # Static assets (images, CSS, JS)
├── src/                 # Main source files
│   ├── controllers/     # Mail functionality and form handling
│   ├── views/           # HTML files (pages like pricing, services, etc.)
│   ├── styles/          # CSS styles
│   ├── scripts/         # Client-side JS for animations and interactions
├── .env                 # Environment variables (Google API, Gmail SMTP)
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## Contributions

### Sunil:
- Developed the **Portfolio**, **Pricing**, and **Press & Media** pages.
- Sourced and selected images for each page.
- Linked all navigation and footer links.

### Sahil Anand:
- Designed the **Services** page with service cards and the FAQ section.

### Kaibalya Sahoo:
- Implemented email functionality with **Nodemailer**.
- Integrated **Google Sheets API** to store form data.
- Resolved issues with the "Get a Quote" button.

### Rajesh Aligeti:
- Refined and rewritten content for multiple sections to improve clarity and engagement.

## Challenges

1. **Credential Sharing Issue**:
   - Solution: Used `.env` files to securely store sensitive information such as API keys and email credentials.

2. **Git Branch Merging**:
   - Solution: Restructured the file hierarchy to ensure smooth merging of features and codebase integration.

