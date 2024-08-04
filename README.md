# PromptFusion

**PromptFusion** is an innovative platform for sharing and discovering AI-generated prompts, designed to inspire creativity and collaboration. Built with modern web technologies, it offers a sleek user experience with features that foster community interaction and ease of use.

## Tech Stack

- **Next.js**: A React framework for building server-side rendered applications.
- **MongoDB**: A NoSQL database for storing prompts and user data.
- **NextAuth**: Authentication library for secure login using Google.
- **TailwindCSS**: A utility-first CSS framework for styling with a modern design.

## Features

- **Modern Design with Glassmorphism Trend**: Sleek and contemporary appearance using the glassmorphism design style.
- **Discover and Share AI Prompts**: Explore prompts shared by the community and create your own to share.
- **Edit and Delete Created Prompts**: Modify or remove your prompts as needed.
- **Profile Page**: View all prompts you’ve created on your dedicated profile page.
- **View Other People's Profiles**: Explore profiles of other creators to see their contributions.
- **Copy to Clipboard**: Conveniently copy prompts for use with a single click.
- **Search Prompts by Specific Tag**: Find prompts related to specific topics with tag-based search.
- **Google Authentication with NextAuth**: Secure login using Google authentication.
- **Responsive Design**: Optimized for a seamless experience across various devices.

## Quick Start

### Prerequisites

Ensure you have the following installed on your machine:

- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

Clone the project repository:

```bash
git clone https://github.com/adrianhajdin/project_next_13_ai_prompt_sharing.git
cd project_next_13_ai_prompt_sharing
```

### Installation

Install the project dependencies:

```bash
npm install
```

### Set Up Environment Variables

Create a `.env` file in the root of your project and add the following content:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```

Replace the placeholder values with your actual credentials. Obtain these credentials from:

- Google Cloud Console for `GOOGLE_ID` and `GOOGLE_CLIENT_SECRET`.
- Cryptpool or a similar service for `NEXTAUTH_SECRET`.
- MongoDB for `MONGODB_URI`.

### Running the Project

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## Contributing

Feel free to submit issues or pull requests to contribute to the development of **PromptFusion**. 

## License

This project is licensed under the MIT License.
