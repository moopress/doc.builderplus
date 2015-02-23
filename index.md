---
layout: page
title: MedicalPlus Documentation
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Instructions on how to install and customize the Jekyll theme Minimal Mistakes."
image:
  feature: banner.jpg
---

{% include _toc.html %}

# Prerequisites

Before you get started creating your site using **MedicalPlus**, you'll need to **setup your WordPress environment**. MedicalPlus requires *WordPress v4.1* or greater. For more information on setting up you WordPress environment please refer to [WordPress Codex "Installing WordPress" entry](http://codex.wordpress.org/Installing_WordPress). If you're experiencing difficulty setting up you WordPress install, you'll need to contact your **hosting company** or your **local system administrator**.

## PHP Configuration
If your server is running PHP `v5.6`, you will need to specify `always_populate_raw_post_data = -1` in your `php.ini` file and reload your web server. This addresses a known bug with the default PHP `v5.6` configuration. For more information on this issue, please see [this blog post](https://www.bram.us/2014/10/26/php-5-6-automatically-populating-http_raw_post_data-is-deprecated-and-will-be-removed-in-a-future-version/). If you find yourself unable to modify your `php.ini` file, please contact your hosting service or site manager.

# Getting Started

## Installing The Theme
1. Unpack the zip that is retrieved from ThemeForest
2. Navigate to `Appearance > Themes`
3. Click `Add New` button
4. Click `Upload Theme`
5. Click `Choose File`
6. From the unpacked directory, select `medicalplus.zip`
7. Click `Install Now`
8. Click `Activate`

**Note:** If you encounter a `style.css not found` error on trying to install the theme, that means that the package you uploaded is the incorrect package. Make sure that you're using the `medicalplus.zip` file from **inside the unzipped package** (*eg.* `<themeforest_unzipped_packaged>/medicalplus.zip`).

## Install Required Plugins
MedicalPlus relies on a number of plugins to provide functionality. In order to install the plugins associated with the theme:

 1. Navigate to `Appearance > Install Plugins` in the admin dashboard 
 4.  Check all the plugins in the list by clicking the top-left most checkbox in the table header.
 5.  Click the `Bulk Actions` select control, choose the `Install` option and click the `Apply` 
 6.  Click the `Return to Required Plugins Installer` link after receiving the "All installations have been completed." 
 7.  Check all the plugins in the list by clicking the top-left most checkbox in the table header.
 8.  Click the `Bulk Actions` select control, choose the `Activate` option and click the `Apply` 
 9.  A notice `The following plugins were activated successfully: ...`

![Install Required Plugins](https://lh5.googleusercontent.com/-RVogUao5W4k/VLQt-DuMXpI/AAAAAAAAAI0/U5eSCsImwoc/s0/Install+Required+Plugins+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress+--+Install.png "Install Required Plugins ‹ MedicalPlus — WordPress -- Install.png")
*Install Required Plugins Page (Install)*

----

![Installation Feedback](https://lh4.googleusercontent.com/--Yrp2RAj6uw/VLQv5N0_dVI/AAAAAAAAAJI/AlRaXJ8zA3g/s0/Install+Required+Plugins+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress+--+Feedback.png "Install Required Plugins ‹ MedicalPlus — WordPress -- Feedback.png")
*Install Required Plugins Page (Feedback)*

----

![Activate Required Plugins](https://lh6.googleusercontent.com/-IK1YLsuNle0/VLQtAJ9x03I/AAAAAAAAAIo/B3Yaelydup0/s0/Install+Required+Plugins+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress.png "Install Required Plugins ‹ MedicalPlus — WordPress.png")
*Install Required Plugins Page (Activate)*

## Using The One-Click Importer
__Before using the one-click importer, make sure to INSTALL & ACTIVATE THE THEME & ALL OF THE REQUIRED & SUGGESTED PLUGINS. If you are planning on using a CHILD THEME, be sure to HAVE THE CHILD THEME ENABLED before running the one-click import.__

The Demo Content Import populates and configures your site content with commonly used pages, posts, and custom post types. That way you can get a site up and working as quickly as possible just by editing the imported pages.

**NOTE:** The one-click import modifies settings and content on your site. Before running the one-click importer, be sure to **backup your site**. Additionally, it's highly recommended that you **only run the one-click import on your site only once**. Multiple runnings of the one-click import will result in *duplicate content*.

 1. Navigate to `Settings > Moo Demo Import` in the admin dashboard
 2. Click the `Import All Content` button
 3. Wait on the page until the feedback indicates that the import is complete.
 4. Your site will be populated and configured with demo content now.

![MooDemo Import Dashboard](https://lh3.googleusercontent.com/-y_qHs0zTXzU/VNTqkLymRnI/AAAAAAAAAMI/yIuzphiI3aY/s0/MooDemo+Import+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress.png "MooDemo Import")
*Demo Import initial page*

----

# Configuring Your Site

## Widget Areas

MedicalPlus provides five widget areas. **Blog Sidebar** -- is the sidebar that's on the blog page. **Footer Column 1-4** are displayed in the footer area. To modify the widgets displayed on the site:

1. Navigate to `Appearance > Widgets`
2. Click and drag desired widgets to appropriate Widget Locations

## Google Fonts

### Setting Available Fonts
Google Fonts provides a library of custom fonts that allow you to customize the font on your site. There are lots of Google Fonts, so you will need to select which ones you want to make available on your site. In order to select your fonts:

1. Navigate to `MooFonts` at the top level of the admin dashboard menu
2. If there are no fonts previewed on the page, click the `Refresh Font List` button in the top right of the page. ![Refresh](https://lh3.googleusercontent.com/-189jEE_zKHE/VLQ0tOpKtmI/AAAAAAAAAKE/2ukJX46NTWs/s0/MooFonts+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress.png "MooFonts ‹ MedicalPlus — WordPress.png")
3. Browse the fonts by scrolling up and down the page. If you have a particular font in mind, use the search box in order to filter the fonts.
4. Once you've decided on a font, click its associated `Add to collection` button
5. This will add the font to the `Your Font Collection` display on the right side of the page.
6. For the font you've added, select the font variants you want available on your site. By selecting the variant checkboxes and the clicking the associated `Save Settings` button.
7. The font & the selected variants will now be available on the site.

![Populated](https://lh5.googleusercontent.com/-hZHFk2wDNAs/VLQ1XB7IXrI/AAAAAAAAAKQ/mB90BBfB7zc/s0/MooFonts+%E2%80%B9+MedicalPlus+%E2%80%94+WordPress+--+populated.png "MooFonts ‹ MedicalPlus — WordPress -- populated.png")
*Populated Fonts*

### Configuring/Customizing Site Fonts

1. Navigate to `Appearance > Customize`
2. Click `Fonts` to open the font options panel
3. Select the desired fonts in the `Heading Font` and `Text Font` dropdowns
4. Click the `Save & Publish` button to save the customizations
5. Now your site will have the specified fonts applied.

![Customize Fonts](https://lh3.googleusercontent.com/-7CRt2IE2eng/VLU-ADLFFLI/AAAAAAAAAK0/tTdobuNwZig/s0/customize-fonts.png "customize-fonts.png")
*Customize Fonts*

## Icon Sets
A number of the shortcodes available when using MedicalPlus, involve icons. By default, the **Font Awesome** icon set is available for use with these shortcodes. In addition to the default icons, you can add icon sets from [Icon Moon](https://icomoon.io). Download a **Font** icon package from Icomoon. To import the package:

1. Navigate to `MooIcons`
2. Click the `Upload Icon Set` button at the top right of the page
3. Upload your `iconmoon.zip` font-icon set
4. Click `Add Font Zip`
5. The icon set will be displayed in preview in the Icon Dashboard. When using icon type shortcodes with Visual Composer, previews of the icon will be available for selection.

![Icon Dashboard](https://lh5.googleusercontent.com/-3P-H8CVxbh0/VLU-gai2RgI/AAAAAAAAALA/_bsGfNtQUsY/s0/icon-dashboard.png "icon-dashboard.png")
*Icon Dashboard*

## Contact Form 7
Contact Form 7 is a plugin that allows for the creation of contact forms on your website. The one-click demo install automatically imports contact forms on to your site. However, before they're ready, you will need to modify the forms so that they send email to your specified email. To edit a contact forms destination email:

1. Navigate to `Contact > Contact Forms` in the admin dashboard
2. Click on the title link of the contact form in the list of forms
3. Locate the `Mail` metabox on the contact for edit page
4. Edit the `To` field.
5. Click the `Save` button to save your change

![Contact Form Edit](https://lh4.googleusercontent.com/-3wsyE8hEpNo/VLU_NqhIHNI/AAAAAAAAALM/wbNJNwqupOc/s0/contact-form.png "contact-form.png")
*Contact Form Edit Page*

----

**NOTE:** Configuration of **email sending is not controlled by MedicalPlus**. If your site is up and running but not sending email, you will need to contact your hosting provider in order to configure and troubleshoot your email sending system.

## Customizer
MedicalPlus provides its site options through the WordPress Customizer. To access the customizer, navigate to `Appearance > Customize` in the admin dashboard. The options that are added by MedicalPlus are organized into panels that can be accessed by clicking on the headers associated with the panels. 

### Customizer Options

* **Fonts**
	* *Heading Font* -- The font that should be applied to headings
	* *Text Font* -- The font that should be applied to general text
* **Header**
	* Header Logo
		* *Logo* -- The image to use for the site logo that appears on the left side of the header
		* *Logo Width* -- The width of the logo element in pixels
		* *Logo Height* -- The height of the logo element in pixels
		* *Logo Top Offset* -- The top offset of the logo element in pixels
		* *Logo Left Offset* -- The left offset of the logo element in pixels
* **Page**
	* Page Body
		* *Page Background Color* -- The default background color of pages on the site
		* *Site Accent Color* -- The color to use for accent elements across the site
* **Blog**
	* *Blog Title* -- The text to display in the subheader when viewing the blog or single post pages.
	* *Authored by text* -- The text to prefix displays of the author in the blog
	* *Posted On* -- The text to prefix displays of the posted on date
* **Footer**
	* Subfooter
		* *Copyright Text* -- The text to display in the copyright section of the subfooter


# Editing Content

## Revolution Slider

 1. Click the `Revolution Slider` menu item in the admin dashboard
 2. In the `Revolution Sliders` metabox
	* Locate the `Fullscreen Slider` slider
	* Click the blue `Edit Slides` button next to it
 3. For each slide
	* Edit the Heading
	* Edit the Subheading
	* Change the link location of the button by editing the `href` attribute of the `a` element
	* Change the background image

## Doctor Profiles

1. Navigate to `Doctors > Department` in the admin dashboard
 2. Use the `Add New Department` Form to create all the applicable departments
 3. Delete the demo departments
 4. Navigate to `Doctors > Doctors` to see the list of demo doctor profiles
 5. For each Doctor in the practice
	* Click the `Doctors > Add New` menu item
	* Enter the name of the doctor as the title (ex. "Dr. John Doe")
	* In the TinyMCE editor, enter the bio of the doctor
	* In the `Excerpt` metabox, enter a short intro to the doctor's bio
	* Fill out the fields in the `Doctor Profile` metabox
	* Use the `Department` metabox to choose the doctor belongs to
	* Use the `Featured Image` metabox to upload a headshot of the doctor
	* Click the blue `Publish` button in the `Publish` metabox
 6. Navigate to `Doctors > Doctors` to see the list of doctor profiles
 7. Delete the demo doctor profiles

## Photos

1. Click the `Photos` menu item (in the admin dashboard) to see a list of demo photos 
 2. For each Photo
	* Click the `Photos > Add New` menu item
	* Enter the title of the photo
	* Use the `Featured Image` metabox to upload the picture
	* Use the `Tags` metabox to enter appropriate tags for the photo
	* Click the blue `Publish` button
 3. Navigate to `Photos > Photos` to see the list of photos
 4. Delete the demo photos

## Testimonials

1. Click the `Testimonials` menu item (in the admin dashboard) to see a list of demo
    testimonials
 2. For each Testimonial
	* Click the `Testimonials > Add New` menu item
	* Enter the name of the person giving the testimonial as the title (ex. "Mr. Sundar Pichai")
	* Enter the actual testimonial into the TinyMCE editor
	* Use the `Featured Image` metabox to upload a headshot of the person giving the testimonial
	* Use the `Testimonial Meta` to enter the name of the company that the person works for (optional)
	* Click the blue `Publish` button
 3. Navigate to `Testimonials > Testimonials` to the list of testimonials
 4. Delete the demo testimonials

## Services

1. Click the `Services` menu item (in the admin dashboard) to see a list of demo services
 2. For each Service the practice offers
	* Click the `Services > Add New` menu item
	* Enter the name of the service in the `Title` field
	* Enter a detailed description of the service in the TinyMCE editor
	* In the `Excerpt` metabox, enter a small summary of the service
	* Use the `Featured Image` metabox to upload a picture relevant to the service
	* Click the blue `Publish` button
 3. Navigate to `Services > Services` to the list of services
 4. Delete the demo services

## Homepage Content

1. Click the `Pages` menu item (in the admin dashboard) to see a list of all demo pages
 2. Locate the `Home` page and click the page title to edit it
 3. Just under the `Title` field and above the TinyMCE editor, locate the dark blue toolbar
 4. Click `Frontend Editor` button in the toolbar
 5. Edit the first row, first column
	* Change the heading text
	* Change the description text
 6. Edit the first row, Icon List Items. For each item
	* Change the heading text
	* Choose a different icon
	* Change the main text
 7. Scroll down and locate the "Advanced Services" row
	* Edit the introductory text
 8. Click the blue `Update` button on the top right of the page
 9. Click the `X` in the top right of the page to exit

## Contact Page Content

1. Click the `Pages` menu item (in the admin dashboard) to see a list of all demo pages
 2. Locate the `Contact` page and click the page title to edit it
 3. Just under the `Title` field and above the TinyMCE editor, locate the dark blue toolbar
 4. Click `Frontend Editor` button in the toolbar
 5. In the first row, first column:
	* Edit the text just below the "Get in Touch" heading
 6. In the first row, second column:
	* Edit the heading so it spells out the name of the practice
	* Edit the address
	* Edit the link URLs of the social icons
 7. In the second row, edit the marker location of the Google Map element

## Page MetaBox Options
MedicalPlus provides a number of page level options to customize the look of individual pages:

* **Hide Subheader** -- hides the subheader page element
* **Subheader Background Color** -- sets the background color of the subheader element
* **Subheader Border Color** -- sets the border color of the subheader element
* **Remove Vertical Page Padding** -- will remove the top and bottom padding of the page content area
* **Page Background Color** -- this option will override the site page background color customization option with whatever color is set.

![Page Metabox](https://lh4.googleusercontent.com/-Y8lrTSqyzmo/VLVAFmXwdpI/AAAAAAAAALg/EE_sytUSM2w/s0/page-metabox.png "page-metabox.png")

## Page Templates
MedicalPlus supplies three page templates: 

* Full Width --  a full width page template that has no sidebar
* Left Sidebar -- a page with a left sidebar
* Right Sidebar -- a page with a right sidebar

For general information on page templates and how to use them in WordPress, see the [WordPress Codex Entry](http://codex.wordpress.org/Page_Templates).

# Shortcodes

* **Animation Block** --*container* shortcode. You can include arbitrary content inside it and set entrance and hover animations to be applied to the content. For more details, refer to the *Animation Block* section below.
* **Counter** -- will count up to a provided numeric value
* **Google Map** -- displays a google map. This is also a *container* shortcode that accepts *Google Map Marker* shortcodes as content.
* **Google Map Marker** -- Used inside the *Google Map* shortcode to define map markers and the content displayed when they are clicked
* **Icon Block** -- A div element that displays an accompanying icon
* **Icon Box** -- A box that displays an accompanying icon
* **Icon Link** -- A link that displays an accompanying icon
* **Icon List** -- A list that displays icons by list items. This is a *container* type shortcode to accommodate 
* **Icon List Item** -- Used inside *Icon List* to define list item icons and content
* **Icon Button Outline** -- an outline style button with an icon displayed in it
* **Icon Button Solid** -- a solid style button with an icon displayed in it
* **Styled Divider** -- a styled horizontal divider for splitting up sections

#Modifying The Theme
Direct code modifications of MedicalPlus are highly discouraged. The recommended way of making modifications to the theme are through the usage of a Child Theme.

## Child Theme
If you are unfamiliar with the concept of a child theme, please refer to the [WordPress Codex entry on Child Themes](http://codex.wordpress.org/Child_Themes). PHP & CSS edits should be made through a child theme. A template child theme is included in the theme package (downloaded from ThemeForest) inside the `resources` directory of the unpacked package.

**Note:** WordPress stores theme customizations on a theme by theme basis. If you've made used the one-click demo or edited the theme customization options with MedicalPlus as your theme instead of your child theme, you will need to export and import your customizations using the [Customizer Import/Export plugin](https://wordpress.org/plugins/customizer-export-import/).

# Miscellaneous

## Permalink Settings

The recommended permalink setting for use with MedicalPlus is the `Post name` default setting in the `Settings > Permalinks` page in the admin dashboard.

## Translation

MedicalPlus supports [Translation](http://codex.wordpress.org/Translating_WordPress) through conventional WordPress translation method. For the translation template for the theme see the theme directory `medicalplus\lang\medicalplus.pot`. For more info on translating with WordPress, see the new [WordPress Handbook entry on translation](https://make.wordpress.org/polyglots/handbook/#).

# Support

All MooPress support is provided through our [Support Ticketing System](http://moopress.ticksy.com/). Please visit and submit a ticket if you can't find an answer in this documentation.

## Finding your purchase code
To submit a ticket, you'll need your theme purchase code. To retrieve it:

1. Navigate in your browser to your ThemeForest Downloads page
2. Find the **MedicalPlus** entry
3. Click the `Download` dropdown and click `License certificate & purchase code (text)`
4. Open the downloaded `txt` file.
5. Locate the `Item Purchase Code:` entry which displays your purchase code