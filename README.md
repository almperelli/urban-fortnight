# Cookie Booth Signup Form

A beautiful, interactive signup form for Girl Scout cookie booth registrations with real-time availability tracking.

## Features

- 🎨 **Modern UI** - Gradient background with smooth animations
- 📅 **Location-based Scheduling** - Different dates/times for each location
- 🔄 **Real-time Availability** - Shows available slots and warns when few remain
- 📱 **Responsive Design** - Works on desktop and mobile devices
- ✅ **Form Validation** - Real-time validation with visual feedback
- 🎯 **Progress Tracking** - Visual progress bar shows completion status
- 💾 **Data Persistence** - Integrates with Data SDK for storage

## How to Use

1. **Clone or download** this repository
2. **Open `index.html`** in a web browser
3. **Fill out the form:**
   - Name and troop information
   - Email address
   - Select a location from the dropdown
   - Choose from available dates for that location
   - Pick an available time slot
4. **Submit** the form to save the registration

## Locations & Scheduling

The form includes pre-configured locations with their own date and time availability:

- **Ace Hardware** - Saturdays, 4 time slots per day
- **Broadway Pub** - Tuesdays, 5 time slots per day  
- **Fuel Cell** - Wednesdays, 4 time slots per day
- **Mt. Bethel Fire** - Fridays, 6 time slots per day
- And more...

## Configuration

You can customize the form by modifying the `defaultConfig` object in the JavaScript:

```javascript
const defaultConfig = {
    form_title: "2026 Cookie Booth Signup",
    form_subtitle: "Let's sell some cookies!",
    submit_button_text: "Submit", 
    success_message: "Mission success! 🎉"
};
