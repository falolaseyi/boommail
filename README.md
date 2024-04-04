To ensure the functionality aligns with our intended design and operational needs, two(2) updates are required.

1. Update Font Delivery Method

Current Approach: The font "Sohne" is currently installed locally on devices. This method may lead to inconsistencies across different environments.

Required Change: The font should be served through our font delivery system to ensure uniformity and accessibility across all platforms.

Example: Instead of relying on local installations, consider hosting the fonts on our server and use CSS @font-face to incorporate it into the templates.


2. Standardize Image Delivery

Current Approach: Images are stored within a directory structure, potentially leading to access issues or broken links in the context of this email.

Required Change: All images should be referenced through absolute URLs. This ensures that images are accessible regardless of where the email is opened or viewed.

Example: Instead of referencing an image like ./images/pic.jpg, we should use full URL path, such as https://ourwebsite.com/images/pic.jpg. This method guarantees that the images are displayed correctly across all email clients and web browsers.

