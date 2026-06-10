# Campsite-Commander
Campsite Commander is an inventory management application designed for outdoor enthusiasts. The app helps users organize camping gear, food supplies, and equipment by categories (Shelter, Food, Safety, First Aid). With an intuitive dark-themed interface and nature-inspired design, it makes trip preparation effortless.

Features:

Splash Screen: 3-second intro with Campsite Commander logo and title animation.
Main Screen: Display total items packed (calculated using loops) with quick access buttons.
Add Item Dialog: Simple interface to add new gear to your packing list dynamically.
Detailed View Screen: Comprehensive list showing all items with:
Item names (highlighted in bright green),
Categories (prominent heading display),
Quantities (in white-bordered boxes),
Comments (in white-bordered boxes).
Navigation: Smooth transitions between screens with "Back to Base" button.
Dark Theme: Professional nature-inspired UI with green accents (#76FF03, #4CAF50).
Parallel Arrays: Efficient data structure for managing items, categories, quantities, comments.
Loop Processing: Uses loops throughout for calculations and dynamic rendering.

Usage Guide

Main Screen
View total number of items currently packed (total calculated from quantities array)
Click "Add Gear" to add new camping items
Click "View Details" to see the full packing list with item information
Adding Items
Opens a dialog asking for item name
Submits with default values:
Category: "Gear"

Quantity: 1
Comments: "Added from app"
Detailed View
Displays all items in card format
Each card shows:
item_name: Bright green header (#76FF03)
Category: Centered heading
Quantity: Inside white-bordered box
Comments: Inside white-bordered box

Click "Back to Base" to return to main screen
