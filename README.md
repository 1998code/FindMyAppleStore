# Find My Store
Easy to find convenience stores in Hong Kong and Tokyo. Made with Apple MapKit JS.

<img width="1332" height="1035" alt="Screenshot 2025-07-26 at 11 53 10 PM" src="https://github.com/user-attachments/assets/86586be9-d62e-4a5e-8f5d-033f77d9e078" />

## Features

### Supported Regions
- **Hong Kong**: 7-Eleven and Circle K
- **Tokyo**: 7-Eleven, FamilyMart, and Lawson

### Store Types & Colors
- **7-Eleven**: Green theme (both regions)
- **Circle K**: Red theme (Hong Kong)
- **FamilyMart**: Light Blue theme (Tokyo)
- **Lawson**: Deep Blue theme (Tokyo)

### Key Features
- Interactive map powered by Apple MapKit JS
- Region-specific store options
- Dynamic color coding for different store chains
- Search and filter functionality
- Responsive design for mobile and desktop
- Dark/Light theme support
- Automatic fallback search for better results

## How to Deploy

1. Clone this project
2. Replace the MapKit token in `index.html`:
   ```javascript
   const tokenID = "YOUR_TOKEN_HERE";
   ```
   Get your token from: https://maps.developer.apple.com/token-maker

3. Deploy to your preferred hosting service (Vercel, Netlify, etc.)

## Usage

1. Select your region (Hong Kong or Tokyo)
2. Choose a store type from the dropdown
3. Click "Search" to find stores
4. Use the search field to filter results
5. Click on any store to center the map on it

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Maps**: Apple MapKit JS
- **Icons**: Font Awesome
- **Hosting**: Vercel (recommended)

## License

MIT License
