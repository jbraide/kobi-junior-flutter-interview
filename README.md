# kobi-junior-flutter-interview

# App Flow Summary

## Input
The screen takes two required parameters via constructor:
- `userName` (String)
- `userBalance` (double)

## UI Structure
- **Scaffold** (Base layout)
  - AppBar with title "User Profile"
  - Body with centered content

## Core Component - Card Widget
- Elevated with shadow (`elevation: 8`)
- Rounded corners (`borderRadius: 12`)
- Internal padding for spacing

## Card Content
- **Header**: "User Details" (styled with `headlineSmall` theme)
- **Two ListTiles** (with icons):
  1. **Name Section**
     - Icon: `Icons.person`
     - Subtitle: Displays `userName`
  2. **Balance Section**
     - Icon: `Icons.account_balance_wallet`
     - Subtitle: Displays formatted balance (e.g., `$1250.50`)

## Action Button
- "Send Money" button at the bottom
- Prints to console on tap (demo action)

## Styling Highlights
- Consistent padding (`EdgeInsets.all(16)`)
- Responsive layout (works on all screen sizes)
- Uses Material Design principles (icons, card elevation, typography)


![Description of the image](WhatsApp%20Image%202025-05-07%20at%2012.58.13.jpeg)
