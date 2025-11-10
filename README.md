# GST & Service Charge Calculator
A simple, clean, and mobile-friendly web app to calculate a final bill amount. This tool applies a service charge to the subtotal first, and then applies GST to the new total.
## ✨ Preview
https://firmanelhakim.github.io/bill-calculator/
## 📋 Features
 * Subtotal Input: Enter your base bill amount.
 * Customizable Rates: Set custom percentages for both Service Charge and GST.
 * Detailed Breakdown: See the exact amounts calculated for:
   * Subtotal
   * Service Charge
   * Total Before GST
   * GST
 * Final Total: A clear, bold display of the final amount payable.
 * Responsive Design: Looks and works great on both desktop and mobile devices.
 * Lightweight: A single HTML file with no external dependencies (uses Tailwind CSS via a CDN).
## 🧮 Calculation Logic
This calculator follows a specific two-step process as requested:
 * Apply Service Charge: The Service Charge percentage is applied first to the Subtotal Amount.
   Total before GST = Subtotal + (Subtotal * Service Charge %)

 * Apply GST: The GST percentage is then calculated based on the new Total before GST (which includes the service charge).
   Final Amount = Total before GST + (Total before GST * GST %)

## 🚀 How to Use
Since this is a single-file application, you can use it instantly:
 * Download: Download the index.html file.
 * Open: Open the file in any modern web browser (like Chrome, Firefox, or Safari).
That's it! No installation or setup is required.
## 🛠️ Technologies Used
 * HTML5
 * Tailwind CSS (for styling, loaded via CDN)
 * JavaScript (for the calculation logic)
## 📄 License
This project is open-source and available under the MIT License.
