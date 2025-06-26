# email-signature-assets

### Prompt to generate HTML from Figma File ###

Prompt v1.0

Convert this Figma frame into a fully responsive HTML email signature, using best practices for email development.
Requirements:

✅ Full HTML Structure:
	•	Provide the complete HTML file starting from <!DOCTYPE html>, including <html>, <head>, and <body> tags.
	•	The email signature should be ready to use as a standalone HTML file.

✅ Responsiveness & Compatibility:
	•	Must render correctly across all major email clients including Outlook, Gmail, Apple Mail, and mobile apps.
	•	Use table-based layout only (no div-based structure).
	•	Use inline CSS only (no <style> tags or external CSS).
	•	Avoid using media queries.

✅ Images & Icons:
	•	Do not convert icons to SVG.
	•	All images and icons should be standard image placeholders (preferably PNG or JPEG) with descriptive alt text.
	•	Use placeholder image paths (e.g., src="image-placeholder.png").
	•	Specify width and height for all images to prevent layout shifting.
	•	No background images—use solid color backgrounds for better email client support.

✅ Design & Dark Mode:
	•	Must display correctly in both dark mode and light mode.
	•	Black and white colors have been used to automatically adapt between modes.
	•	For lighter text, I’ve used a specific grey color that works well in both modes — this must remain unchanged.

✅ Styling:
	•	All links must have text-decoration: none; and maintain proper accessibility contrast.
	•	Fallback fonts: Arial, Helvetica, sans-serif.
	•	All text must be selectable and live (no text as images).
	•	Avoid fixed heights to ensure flexible rendering across email clients.
	•	Use padding and spacing carefully to ensure consistent alignment.

✅ Functionality & Accessibility:
	•	All phone numbers, email addresses, and URLs must be clickable.
	•	The signature must degrade gracefully when images are disabled.
	•	Provide a version that can be previewed with and without images loaded.

✅ Deliverables:
	•	Full, production-ready HTML file with complete structure and inline CSS.
	•	Include clear comments in the code where images, icons, or text will need to be updated.

✅ Important:
	•	Do not use SVGs. Only use raster image placeholders (PNG or JPEG).
	•	Use only email-safe, web-standard fonts.