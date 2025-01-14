# Dropdown Components Project

## Overview
This project contains four customizable dropdown components designed for different use cases and user interfaces. Each dropdown demonstrates unique features, styles, and interaction mechanisms, providing a comprehensive foundation for dropdown implementations in web applications.

## Components

### 1. Dropdown-1
A simple dropdown with profile-related options.
- **Features:**
  - Toggles open/close states with a button click.
  - Closes when clicking outside the dropdown.
  - Options include Profile, Settings, and Account.
- **Key Libraries Used:**
  - React Hooks (`useState`, `useRef`, `useEffect`)

### 2. Dropdown-2
An advanced dropdown with dynamic menu positioning.
- **Features:**
  - Dynamically positions the menu based on button and chevron alignment.
  - Options include Dark Mode, Widgets, and Account.
- **Key Libraries Used:**
  - React Hooks (`useState`, `useRef`)
  - Custom dynamic styling for precise menu placement.

### 3. Dropdown-3
A dropdown integrated with a Swiper carousel for skills display.
- **Features:**
  - Displays skills grouped under Development, Design, and Deployment.
  - Integrates a Swiper carousel for navigation within the dropdown.
  - Menu items include tools like HTML, CSS, React, Figma, Netlify, and more.
- **Key Libraries Used:**
  - `swiper/react` for carousel functionality.
  - `swiper/css` for styling.

### 4. Dropdown-4
A hierarchical dropdown menu with submenus.
- **Features:**
  - Displays main menu items with nested submenus.
  - Smooth transitions between main menu and submenus.
  - Options include Build, Devices (with sub-items like Storage, Mouse, etc.), and Logout.
- **Key Libraries Used:**
  - React Hooks (`useState`, `useRef`)
  - Flexible menu height adjustments for smooth transitions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dropdowns-project.git
   cd dropdowns-project
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the project:
   ```bash
   npm start
   ```

## Folder Structure
- **src/**: Contains all source code for the project.
  - **Dropdown1/**: Code for the first dropdown.
  - **Dropdown2/**: Code for the second dropdown.
  - **Dropdown3/**: Code for the third dropdown.
  - **Dropdown4/**: Code for the fourth dropdown.
  - **styles.css**: Shared styles for all dropdowns.
  - **assets/**: Includes images and other assets like SVG files and logos.

## Customization
Each dropdown component can be customized by editing its corresponding file under the `src/` directory. You can:
- Modify menu items and their labels.
- Change icons using Material Symbols.
- Adjust styles in `styles.css`.

## Dependencies
- React
- Swiper
- Material Symbols (for icons)

## Contribution
Feel free to submit issues or create pull requests for any improvements or bugs you encounter. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or support, please contact:
- **Name**: Aras
- **GitHub**: [github.com/your-username](https://github.com/your-username)
- **Email**: your-email@example.com

