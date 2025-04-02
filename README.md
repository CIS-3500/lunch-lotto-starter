# CIS 3500: Lunch Lotto Starter

## Overview
This assignment involves enhancing a Chrome extension developed by one of the Top 3 winners of the MCIT hackathon. The project provides hands-on experience in web development, API integration, and collaborative coding.

**Original project:** [Lunch Lotto](https://github.com/jessie-sr/lunch-lotto)

## Project Description
Lunch Lotto is a Chrome extension that helps users decide where to eat by randomly selecting nearby restaurants. Your task is to enhance this extension by implementing new features.

## Enhancement Options
Choose one of the following enhancements to implement:

1. **History Feature**: Maintain a log of all restaurants chosen by the user.
   - Create a storage mechanism using Chrome's `chrome.storage.local` API
   - Add functionality to save each selected restaurant with timestamp
   - Implement a UI panel to display history entries
   - Add options to clear history or remove individual entries

2. **Alternative API Integration**: Replace Google Maps API with another restaurant data provider.
   - Research alternative APIs (Yelp, Foursquare, OpenTable, etc.)
   - Register for API credentials with the chosen provider
   - Refactor the data fetching logic to use the new API
   - Update the data parsing to match the new API's response format
   - Modify the UI to accommodate any new data fields

3. **Progress Indicator**: Add a progress bar to indicate the status of API calls.
   - Design a progress bar component that fits the extension's UI
   - Implement event listeners for API call start, progress, and completion
   - Add animation for smoother visual feedback
   - Include error state visualization for failed requests

4. **Caching Mechanism**: Add a caching mechanism to the API calls so that on reload of the page, another API call doesn't have to be made.
   - Implement cache storage using Chrome's storage API or IndexedDB
   - Add logic to check cache before making new API calls
   - Set appropriate cache expiration times
   - Add cache invalidation for location changes
   - Include a manual refresh option to bypass cache

5. **Custom Feature**: Propose a unique feature (requires instructor/TA approval).
   - Submit a brief proposal document outlining your feature idea
   - Include implementation approach and technical requirements
   - Get explicit approval before beginning development
   - Document your implementation process

## Getting Started

### Step 1: Team Organization
- Assign a team member as the **Product Manager (PM)** for Lunch Lotto.
- Ensure this PM is different from the one assigned to the Nara project.

### Step 2: Repository Setup
The PM should fork the repository:
1. Navigate to the `lunch-lotto-starter` repository on GitHub.
2. Click the **Fork** button to create a copy under their account.

### Step 3: Cloning the Repository
Once the PM has forked the repository, team members should clone it locally:
```sh
git clone https://github.com/<PM-username>/lunch-lotto-starter.git
```

### Step 4: Development Workflow
1. Open the project in a text editor (e.g., **Visual Studio Code** recommended).
2. Make changes to the codebase.
3. Use the following commands to commit and push your changes:

```sh
git add .
git commit -m "feat: [feature name] added"
git push
```

4. As team members contribute, collaborate using **Pull Requests (PRs)** on GitHub.
5. Regularly sync your local repository with the latest changes:

```sh
git pull
```

6. Resolve merge conflicts as needed and ensure smooth integration.

## Submission
- Submit the final version of your project as per website guidelines.
- Include a brief write-up of your implemented features and any challenges faced.

---
Happy coding, and good luck with Lunch Lotto! 🍀
