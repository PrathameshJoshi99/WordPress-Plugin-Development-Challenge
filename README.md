# WordPress-Plugin-Development-Challenge

# Testimonials Plugin

**Version:** 1.0  
**Author:** Your Name  
**License:** GPL-2.0+  
**Tested up to:** WordPress 5.8

## Description

The Testimonials Plugin is a WordPress plugin that allows you to easily add and manage testimonials on your website. It creates a "Testimonials" custom post type and provides a user-friendly interface for administrators to add, edit, and delete testimonials. Users can also customize the display style, colors, and fonts of testimonials using simple settings.

## Installation

1. Upload the `testimonials-plugin` directory to the `/wp-content/plugins/` directory of your WordPress installation.

2. Activate the plugin through the 'Plugins' menu in WordPress.

## Configuration

Once the plugin is activated, follow these steps to configure and use it:

1. **Customize Testimonial Display:**
   - Go to the WordPress admin dashboard.
   - Navigate to the "Testimonial Customization" menu.
   - Here, you can customize the display style, text color, and font family for testimonials.

2. **Add Testimonials:**
   - In the WordPress admin dashboard, click on "Testimonials" in the sidebar menu.
   - Click "Add New" to create a new testimonial.
   - Fill in the testimonial details, including name, position, company, and testimonial content.
   - Click "Publish" to save the testimonial.

3. **Display Testimonials on Your Site:**
   - Use the `[display_testimonials]` shortcode to display testimonials on any post or page.
   - Example shortcode: `[display_testimonials count="5" order="random"]`

## Usage

### Shortcode Attributes

- `count` (optional): The number of testimonials to display. Default is `-1` to display all testimonials.
- `order` (optional): The order in which testimonials are displayed. Options: `date` (default) or `random` for random order.

Example usage of the shortcode:


### Admin Management

- In the admin dashboard, navigate to "Testimonials" to add, edit, and delete testimonials.
- Testimonials are listed in a user-friendly table view with columns for name, position, company, and more.

## Security

Please ensure your WordPress installation, themes, and plugins are kept up to date to maintain the security of your website. Additionally, this plugin performs data validation and sanitation to prevent common security vulnerabilities.

## Frequently Asked Questions

#### How do I change the display style of testimonials?

- Go to the "Testimonial Customization" menu in the admin dashboard.
- Customize the display style, text color, and font family.

#### Can I display testimonials in a random order?

- Yes, you can use the `order="random"` attribute in the `[display_testimonials]` shortcode to display testimonials in random order.

## Support

For support or questions, please contact [Your Contact Information].

## License

This plugin is released under the GPL-2.0+ License. See the `LICENSE` file for more details.

