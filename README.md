# Odin Admin Dashboard

A modern, responsive admin dashboard built with HTML and CSS as part of The Odin Project curriculum. This project demonstrates advanced CSS Grid and Flexbox techniques to create a professional-looking dashboard interface.

## 🚀 Features

- **Responsive Design**: Built with CSS Grid and Flexbox for optimal layout across different screen sizes
- **Modern UI**: Clean, professional interface with hover effects and smooth transitions
- **Interactive Elements**: Clickable navigation items, buttons, and project cards
- **Sidebar Navigation**: Collapsible sidebar with icon-based navigation
- **Project Management**: Grid-based project cards with action buttons
- **Announcements Section**: Real-time updates and notifications
- **Trending Users**: Social features showing trending profiles
- **Search Functionality**: Integrated search bar in the header

## 📁 Project Structure

```
odin-admin-dashboard/
├── index.html          # Main HTML structure
├── style.css           # CSS styles and layout
├── README.md           # Project documentation
└── src/                # Assets directory
    ├── *.png           # Custom navigation icons
    ├── *.svg           # UI icons and graphics
    └── *.jpg           # Profile images and avatars
```

## 🎨 Design Features

### Layout
- **CSS Grid**: Main container uses CSS Grid for responsive layout
- **Sidebar**: Fixed sidebar with navigation menu (1fr width)
- **Main Content**: Flexible content area (3fr width)
- **Two-Column Content**: Projects on left, announcements/trending on right

### Styling
- **Color Scheme**: Blue (#0ea5e9) primary color with white backgrounds
- **Typography**: Roboto font family for modern, clean text
- **Shadows**: Subtle box shadows for depth and visual hierarchy
- **Hover Effects**: Interactive elements with smooth transitions
- **Border Radius**: Rounded corners for modern appearance

### Components
- **Navigation Sidebar**: Icon-based menu with dashboard, profile, messages, etc.
- **Header**: Search bar, notifications, and user profile
- **Project Cards**: Grid layout with project descriptions and action buttons
- **Announcements**: Vertical list of site updates and news
- **Trending Section**: User profiles with avatars and descriptions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with Grid, Flexbox, and modern features
- **Google Fonts**: Roboto font family
- **SVG Icons**: Scalable vector graphics for UI elements
- **Responsive Design**: Mobile-first approach with flexible layouts

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shawn2093/odin-admin-dashboard.git
   cd odin-admin-dashboard
   ```

2. **Open in browser**:
   - Simply open `index.html` in any modern web browser
   - No build process or dependencies required

3. **Customize**:
   - Modify `style.css` for styling changes
   - Update `index.html` for content changes
   - Replace images in `src/` directory as needed

## 📱 Responsive Design

The dashboard is built with a mobile-first approach:
- **Desktop**: Full sidebar and two-column content layout
- **Tablet**: Responsive grid that adapts to screen size
- **Mobile**: Stacked layout with optimized spacing

## 🎯 Key Learning Objectives

This project demonstrates:
- CSS Grid for complex layouts
- Flexbox for component alignment
- Responsive design principles
- Modern CSS features (custom properties, transitions)
- Semantic HTML structure
- Icon integration and asset management

## 🔧 Customization

### Adding New Navigation Items
1. Add new `<li>` elements in the sidebar `<ul>`
2. Include appropriate icon from `src/` directory
3. Update CSS if needed for styling

### Modifying Project Cards
1. Add/remove project cards in the `.content-projects` div
2. Update project titles and descriptions
3. Customize action buttons as needed

### Changing Color Scheme
1. Update CSS custom properties in `style.css`
2. Primary color: `#0ea5e9`
3. Background colors and text colors can be easily modified

## 📄 License

This project is part of The Odin Project curriculum and is for educational purposes.

## 🤝 Contributing

This is an educational project, but suggestions and improvements are welcome!

## 📞 Contact

Created by Shawn Ong (@shawn2093) as part of The Odin Project learning path.

---

*Built with ❤️ using HTML, CSS, and modern web development practices*