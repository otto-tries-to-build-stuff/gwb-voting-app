# Gentlemen Who Brunch - Voting App

A fun, interactive voting application designed for brunch groups to vote on the "Most Dapper Gentleman" (MDG) at each event.

## 🥐 Overview

This web-based application allows brunch group members to vote for the Most Dapper Gentleman at each gathering. The app features a distinctive retro-diner aesthetic with warm orange and cream colors, bold typography, and playful animations.

## ✨ Key Features

### Voting System
- **Flexible Point Allocation**: Voters assign 3, 2, and 1 point to different members
- **Smart Voting Rules**:
  - Small groups (3 or fewer voters): Can vote for the same person multiple times
  - Larger groups (4+ voters): Must vote for different people
  - Optional vote assignment: Can skip votes with warning confirmation
  - Must assign at least one vote to submit
- **Sequential Voting**: Each member votes privately on the same device
- **Anti-Self-Voting**: Members cannot vote for themselves

### Event Management
- **Create New Events**: Set event name, date, and select attending members
- **Default Members**: Otto, AK, Pete, Danny, Monty, Karl, Jordan, Isaac
- **Member Selection**: Add or remove members based on attendance
- **Event History**: View all past events with winner information
- **Event Details**: See event name, date, winner, full score breakdown, and voting participants

### Results & Analytics
- **Dramatic Winner Reveal**: 3-2-1 countdown with confetti animation
- **Tie Detection**: Automatically detects and announces ties with all tied winners
- **Full Score Breakdown**: See everyone's total points ranked from highest to lowest
- **Random Brunch Emoji**: Different celebratory emoji for each winner reveal (🥐🥞🧇🥓🍳☕🥖🧈)
- **Voting Breakdown** (Dispute Resolution): View detailed individual votes with double-confirmation warning

### Data Management
- **Recycle Bin**: Deleted events move to recycle bin instead of permanent deletion
- **Restore Events**: Recover accidentally deleted events from recycle bin
- **Empty Recycle Bin**: Permanently delete all recycled events
- **Persistent Storage**: All data saved locally in browser (survives page refreshes)

### User Interface
- **Champagne Animation**: Home screen features clinking champagne glasses that transform into cycling brunch foods
- **Retro-Diner Aesthetic**: Bold "Righteous" font with layered text shadows and offset button shadows
- **Mobile-Friendly**: Responsive design optimized for phone and desktop
- **Smooth Animations**: Confetti effects, slide transitions, and micro-interactions

## 📱 How to Use

### Getting Started
1. Open the HTML file in any modern web browser
2. Bookmark the page or add to home screen for easy access

### Creating a Vote
1. Click "Create New Vote" from home screen
2. Enter event name and date
3. Select which members attended (default: all members checked)
4. Click "Vote Now" (button activates when name and date are filled)

### Voting Process
1. First voter sees their name and voting options
2. Assign 3, 2, and 1 point to different members (or same member for small groups)
3. Click "Submit Vote"
4. Pass phone to next voter
5. Repeat until all members have voted

### Viewing Results
1. After final vote, pass phone to reigning MDG
2. Click "Reveal the Winner"
3. Watch 3-2-1 countdown
4. Winner revealed with confetti and random brunch emoji
5. View full score breakdown
6. Optional: Click "View Voting Breakdown" for detailed vote audit (with warning)

### Managing History
- **View Events**: Click "View History" to see all past events
- **Event Details**: Click any event to see full details including scores
- **Delete Event**: Click "Delete Event" from event detail page
- **Recycle Bin**: Access from history screen to view/restore deleted events
- **Empty Recycle Bin**: Permanently delete all events in recycle bin

## 🔒 Data & Privacy

- All data stored locally in browser's localStorage
- No internet connection required after initial page load
- Each device/browser has separate data storage
- Clearing browser data will delete all events
- Desktop and mobile browsers maintain separate histories

## 🛠️ Technical Details

- **Technology**: Single-file HTML with embedded CSS and JavaScript
- **Storage**: Browser localStorage API
- **Fonts**: Google Fonts - "Righteous" (display) and "Cabin" (body)
- **No Dependencies**: Pure vanilla JavaScript, no frameworks required
- **Browser Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## 📋 Version History

### Version 1.0 - Initial Release
**Core Features:**
- Create new votes with event name and date
- Default member list with add/remove capability
- Sequential voting system
- 3-2-1 countdown and winner reveal
- Basic event history
- Persistent localStorage

### Version 1.1 - Recycle Bin
**Added:**
- Delete events functionality
- Recycle bin for deleted events
- Restore events from recycle bin
- Empty recycle bin feature

### Version 1.2 - Enhanced Results
**Added:**
- Full score breakdown on winner screen
- Tie detection and announcement
- Scores displayed in event history
- Ranked score display (1st place highlighted)

### Version 1.3 - UI Enhancement
**Changed:**
- Replaced static subtitle with champagne clinking animation
- Cycling brunch food emojis (changes every 4 seconds)
- Enhanced home screen aesthetic

### Version 1.4 - Voting Breakdown (Current)
**Added:**
- "View Voting Breakdown" feature with warning confirmation
- Detailed individual vote display in modal
- Available on winner screen and event history
- Privacy warning to maintain voting integrity
- Isaac added to default members list

**Changed:**
- Flexible voting rules for small groups (≤3 voters can vote for same person)
- Optional vote assignment with confirmation warning
- Must assign at least one vote to submit
- Improved vote validation logic
- Updated terminology from "Most Distinguished Gentleman" to "Most Dapper Gentleman" (MDG)
- Increased spacing between event lists and action buttons on history/recycle bin screens

## 🎯 Future Considerations

Potential features that could be added:
- **Cloud Sync**: Share voting history across devices using Firebase or similar
- **Multi-Device Voting**: Everyone votes on their own phone simultaneously
- **Statistics Dashboard**: Track win rates, average scores, attendance patterns
- **Custom Animations**: More brunch-themed animations and effects
- **Export Results**: Download voting history as PDF or spreadsheet
- **Photo Upload**: Add photos from each brunch event
- **Rematch Feature**: Quickly create new vote with same members

## 📞 Support

For issues or questions:
- Review this README for feature explanations
- Check browser console (F12) for debugging information
- Ensure browser supports localStorage
- Try clearing browser cache if experiencing issues

## 🎉 Credits

Created for the Gentlemen Who Brunch group to add fun and friendly competition to their gatherings!

---

**Version**: 1.4  
**Last Updated**: February 2026  
**Maintained by**: The Reigning MDG 👑
