# Ticket Genie - Cybersecurity Ticketing System

Ticket Genie is a cybersecurity ticketing system built with Next.js, Tailwind CSS, and MongoDB. It provides full CRUD (Create, Read, Update, Delete) functionality for managing support tickets. The app is designed with a user-friendly interface, enabling seamless ticket submission and management, with optimized MongoDB integration for efficient data storage.

## Features
- **Full CRUD Operations**: 
  - Easily create, update, view, and delete support tickets.
- **User-friendly Interface**: 
  - Simple and intuitive design for a smooth user experience.
- **Optimized MongoDB**: 
  - Efficient data handling and storage with MongoDB, using Mongoose as the ORM.
- **Next.js 13.4**:
  - Built with the latest app router to make the development process easier and more flexible.

## Tech Stack
- **Next.js 13.4**: 
  - Leverages the Next.js app router for optimal routing and server-side functionality.
- **Tailwind CSS**: 
  - A utility-first CSS framework for rapid UI development and custom designs.
- **MongoDB**: 
  - A NoSQL database used to store and manage tickets efficiently.
- **Mongoose**: 
  - Provides schema-based solutions to model application data.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/YashitaCodes/ticket-genie.git
    cd ticket-genie
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up your environment variables:
   - Create a `.env.local` file in the root directory with the following:
     ```bash
     MONGODB_URI=mongodb+srv://yourUSER:yourPASSWORD@cluster0.ukunedo.mongodb.net/MondayClone
     ```

4. Run the development server:
    ```bash
    npm run dev
    ```

   - Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

- **Creating Tickets**: Navigate to the "Create Ticket" section, enter the required details, and submit your ticket.
- **Viewing Tickets**: Access all submitted tickets in the "Ticket List" section. Tickets are displayed with details such as ID, status, and description.
- **Updating Tickets**: Click on any ticket to view its details and modify the status or description.
- **Deleting Tickets**: Easily remove tickets that are no longer relevant with a single click.

## Future Updates
- **Authentication**: Implementing authentication actions and protected routes with auth providers like Auth.js, Clerk or Kinde.
- **Documentation**: Full deployment guide with instructions for platforms like Vercel and DigitalOcean.
- **Next.js 14 Features**: Planning to incorporate new features as they become available in Next.js 14.

---

### Credits
This project was inspired by [Clarity Coders](https://www.youtube.com/claritycoders) YouTube channel. Check them out for more amazing tutorials and coding insights!