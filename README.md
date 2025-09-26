# Annadan - Food Waste Reduction Network

A React-based web application that connects food donors with recipients to reduce food waste and combat food insecurity.

## Features

- **Multi-user Platform**: Support for individual users, businesses, NGOs, and volunteers
- **User Registration**: Separate signup flows for different user types
- **Dashboard Management**: Personalized dashboards for each user type
- **Donation Management**: Easy-to-use forms for posting and managing food donations
- **Request System**: NGOs can post requests for specific food items
- **Volunteer Coordination**: Volunteers can view and accept pickup/delivery tasks
- **Real-time Statistics**: Track impact through meals served, people helped, and carbon footprint reduction

## User Types

1. **Individual Users**: Donate food from home events (weddings, parties, etc.)
2. **Business Owners**: Restaurants and stores donating surplus food
3. **NGOs/Recipients**: Organizations receiving food donations for distribution
4. **Volunteers**: Help with food pickup and delivery logistics

## Tech Stack

- **Frontend**: React 18.2.0
- **Routing**: React Router DOM 6.8.1
- **Styling**: Tailwind CSS (via CDN)
- **Icons**: Font Awesome 6.0.0
- **Build Tool**: Create React App

## Installation

1. **Clone or download the project**
   ```bash
   cd path/to/annadan-project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application.

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Project Structure

```
src/
├── components/
│   ├── Home.js                 # Landing page
│   ├── Signup.js              # User type selection
│   ├── UserSignup.js          # Individual user registration
│   ├── UserDashboard.js       # Individual user dashboard
│   ├── BusinessSignup.js      # Business registration
│   ├── BusinessDashboard.js   # Business dashboard
│   ├── NGOSignup.js          # NGO registration
│   ├── NGODashboard.js       # NGO dashboard
│   ├── VolunteerSignup.js    # Volunteer registration
│   ├── VolunteerDashboard.js # Volunteer dashboard
│   └── BusRoutes.js          # NGO requests view
├── App.js                     # Main app component with routing
├── index.js                   # App entry point
└── index.css                  # Global styles
```

## Routes

- `/` - Home/Landing page
- `/signup` - User type selection
- `/user-signup` - Individual user registration
- `/user-dashboard` - Individual user dashboard
- `/business-signup` - Business registration
- `/business-dashboard` - Business dashboard
- `/ngo-signup` - NGO registration
- `/ngo-dashboard` - NGO dashboard
- `/volunteer-signup` - Volunteer registration
- `/volunteer-dashboard` - Volunteer dashboard
- `/bus-routes` - View NGO requests

## Key Features by User Type

### Individual Users
- Register with personal details and donation sources
- Add food donations with pickup times and locations
- Track personal impact (meals donated, people served, CO₂ saved)
- View donation history and status

### Business Owners
- Register with business details and FSSAI license
- Post surplus food donations with expiry times
- Track business impact and community contribution
- Manage upcoming donations and assignments

### NGOs/Recipients
- Register with organization details and documentation
- Post requests for specific food items with urgency levels
- Manage active requests and community needs
- Connect with donors and volunteers

### Volunteers
- Register with vehicle and availability details
- View available pickup/delivery tasks
- Accept volunteer assignments
- Help coordinate food distribution

## Development Notes

- All forms include proper validation and state management
- Responsive design works on desktop and mobile devices
- Uses React hooks for state management
- Navigation handled through React Router
- Mock data used for demonstration purposes
- Ready for backend integration

## Future Enhancements

- Backend API integration
- Real-time notifications
- GPS tracking for deliveries
- Payment gateway for donations
- Advanced analytics and reporting
- Mobile app development
- Multi-language support

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please contact the Annadan development team.

---

**Annadan** - Making a difference, one meal at a time. 🍽️💚
