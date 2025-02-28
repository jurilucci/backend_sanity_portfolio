# :rocket: Juri Lucci Portfolio - Sanity Backend

## Features

- **Structured Content**: Well-defined schemas for all portfolio sections
- **User-friendly Interface**: Easy content management through Sanity Studio
- **Real-time Content**: Changes reflect immediately in the Sanity data store
- **Asset Management**: Built-in image handling with hotspot functionality
- **Flexible Schema**: Customizable content structure

## Technologies Used

- Sanity.io CMS
- React (for Sanity Studio)
- JavaScript

## Content Models

The CMS is configured with the following data models:

- **About**: Personal information and description sections
- **Skills**: Technical skills with icons and customizable background colors
- **Experiences**: Work experiences organized by year
- **Works**: Projects with images, descriptions, and links
- **Testimonials**: Feedback and reviews from clients or colleagues
- **Contact**: Contact form submissions
- **Brands**: Logos and names of brands or technologies used

## Setup and Installation

### Prerequisites
- Node.js (v14.0 or later)
- npm or yarn
- Sanity CLI (optional but recommended)

### Installation

1. Install Sanity CLI (if not already installed)
   ```
   npm install -g @sanity/cli
   ```

2. Clone the repository
   ```
   git clone https://github.com/yourusername/backend_sanity_portfolio.git
   cd backend_sanity_portfolio
   ```

3. Install dependencies
   ```
   npm install
   ```

4. Start Sanity Studio
   ```
   npm start
   ```
   
   The studio will be available at: http://localhost:3333

## Sanity Studio Configuration

If you need to reconfigure the Sanity studio (e.g., connect to a different project):

1. Login to your Sanity account
   ```
   sanity login
   ```

2. Initialize a new project (if needed)
   ```
   sanity init
   ```
   Follow the prompts to configure your project

## Content Management

### Adding Content

1. Navigate to the appropriate content type in Sanity Studio
2. Click the "Create new" button
3. Fill in the required fields
4. Click "Publish" to make the content live

### Managing Assets

- Images can be uploaded directly in the studio
- The "hotspot" feature allows you to control how images are cropped at different screen sizes

## Deployment

To deploy Sanity Studio to a public URL:

```
sanity deploy
```

This will make your Sanity Studio available at a public URL (usually `https://yourproject.sanity.studio`).

## API Access

To use this content in your frontend application:

1. Generate an API token in the Sanity management console
2. Use the projectId, dataset name, and token in your frontend configuration

## Additional Resources

- [Sanity Documentation](https://www.sanity.io/docs)
- [GROQ Query Language](https://www.sanity.io/docs/groq)
- [Sanity Content Lake](https://www.sanity.io/docs/datastore)
