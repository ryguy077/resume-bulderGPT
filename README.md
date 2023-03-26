# Resume Builder

This Resume Builder is a React web application that creates professional resumes using OpenAI GPT-4 and saves user data to a Google Sheets document for lead generation. Users can preview their generated resume and download it in various formats.

## Features

- Beautiful landing page with a user-friendly form
- Generates resumes using OpenAI GPT-4
- Previews generated resumes
- Downloads resumes in multiple formats (Word, PDF, etc.)
- Saves user data to Google Sheets for lead generation
- Hides API keys and environment variables when deployed to Vercel

## Getting Started

### Prerequisites

- Node.js installed
- OpenAI API key for GPT-4
- Google Sheets API key and client email

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/resume-builder.git
```

2. Install the required packages:

```bash
cd resume-builder
npm install
```

3. Set up the `.env` file:

Create a `.env` file in the root of the project with the following variables:

```
REACT_APP_OPENAI_API_KEY=YOUR_API_KEY
REACT_APP_GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
REACT_APP_GOOGLE_CLIENT_EMAIL=YOUR_GOOGLE_CLIENT_EMAIL
REACT_APP_SPREADSHEET_ID=YOUR_SPREADSHEET_ID
```

Replace the placeholders with your respective API keys and values.

4. Run the application locally:

```bash
npm start
```

The application should now be running at `http://localhost:3000`.

### Deployment

To deploy the application to Vercel:

1. Install the Vercel CLI:

```bash
npm i -g vercel
```

2. Deploy the project:

```bash
vercel
```

Follow the prompts to set up your project, link it to your Vercel account, and add the environment variables from your `.env` file. The deployed application will have the API keys and environment variables hidden.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
