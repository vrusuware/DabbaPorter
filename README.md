# DabbaPorter
DabbaPorter is a smart and reliable delivery app that connects users with dabbawalas for fast and efficient service. Whether it's delivering fresh home-cooked tiffins or sending important items across the city, DabbaPorter ensures convenience, punctuality, and trust—all in one easy-to-use platform.

# DabbaPort

A comprehensive web application for tiffin and porter delivery services, connecting users with local food providers through an advanced platform with intelligent ordering, real-time tracking, and personalized dining experiences.

## Features

- **Authentication**: Complete authentication system with registration, login, email verification, and four distinct user roles (CUSTOMER, DABBAWALA, TIFFIN HOUSES, and ADMIN).
- **Payment Integration**: Secure Razorpay payment integration with Cash on Delivery as an alternative.
- **Role-Based Access**: Specialized dashboards for different user types, including a dabbawala dashboard showing only assigned orders.
- **Real-Time Tracking**: Location tracking for dabbawalas with accurate delivery time estimates.
- **Order History Visualization**: Charts showing trends, tiffin house preferences, and day-of-week patterns.
- **Search Functionality**: Search by both tiffin house names and dish names.
- **Mobile-Responsive Design**: Originally envisioned as a mobile app, adapted for web with responsive design.

## Key Technologies

- **Frontend**: React.js with TypeScript
- **State Management**: React Context API with React Query
- **Backend**: Node.js with Express.js
- **Database**: PostgreSQL with Drizzle ORM
- **Payment**: Razorpay integration
- **Location Services**: Real-time GPS tracking
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with Shadcn UI
- **Email Services**: Integrated notification system

## User Roles

- **CUSTOMER**: Order food from tiffin houses, hire porter services, track orders
- **DABBAWALA**: View assigned orders, update delivery status, share location
- **TIFFIN HOUSES**: Manage menu items, accept/reject orders, track sales
- **ADMIN**: Global dashboard, manage all users, reporting

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables in `.env`
4. Start the application: `npm run dev`

## Database Export and Migration

DabbaPort includes a database export feature to help you migrate data to other environments:

1. **Export Database**:
   ```
   node export-database.js
   ```
   This will create a file called `database-export.json` with all your application data.

2. **Migrate to Another Database**:
   See `MIGRATION_GUIDE.md` for detailed instructions on importing this data to other PostgreSQL instances or different database systems.

## Environment Variables

The application requires several environment variables:

- `DATABASE_URL`: PostgreSQL connection string
- `RAZORPAY_KEY_ID`: Razorpay API key ID
- `RAZORPAY_KEY_SECRET`: Razorpay secret key
- `GMAIL_USER`: Gmail account for sending emails
- `GMAIL_APP_PASSWORD`: Gmail app password (for email notifications)

## License

MIT


**IF YOU WANT THE FULLY FUNCTIONAL PROJECT AND HELP WITH IT, KINDLY CONTACT ON THE BELOW MAIL ADDRESS**
**vrunu03@gmail.com**


**IF YOU WANT THE FULLY FUNCTIONAL PROJECT AND HELP WITH IT****IF YOU WANT THE FULLY FUNCTIONAL PROJECT AND HELP WITH IT****IF YOU WANT THE FULLY FUNCTIONAL PROJECT AND HELP WITH IT**
