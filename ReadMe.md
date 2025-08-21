# CSS_Sidebar_Menu_Project

A clean and responsive sidebar navigation menu built using HTML and CSS. The sidebar features a **hamburger menu toggle implemented with a hidden checkbox input**, and uses Font Awesome icons for a modern appearance.

[![Watch the video](assets/sidebar_menu_working.png)](assets/Sidebar_menu.mp4)

## Features

- Responsive sidebar navigation compatible with desktop and mobile devices  
- Hamburger menu toggle controlled by a hidden checkbox input for smooth CSS-only interaction  
- Integrated Font Awesome icons for navigation and social links  
- Minimal and elegant design with customizable background

## How It Works
- A hidden checkbox (`#check`) is used as a toggle.
- When checked, the sidebar slides into view using:

  ```css
  #check:checked ~ .sidebar_menu {
      left: 0;
  }
  
## Technologies Used
- **HTML5**
- **CSS3**
- **Google Fonts (Poppins)**
- **Font Awesome Icons**

## Getting Started

To use this project locally:

1. Clone or download this repository.  
2. Open `index.html` in your preferred web browser.  

## Customization

- Change the background by replacing the `camera_photo.jpg` image file.  
- Edit navigation links and menu items within the `index.html` file.  
- Modify styles in the `style.css` file to update colors, fonts, and layout.  

## License

This project is open source and free to use under the MIT License.  

---

Created by Manav Juneja
