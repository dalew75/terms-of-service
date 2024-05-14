# Terms Of Service Tracker

A Git repository dedicated to maintaining a history of Terms and Conditions for various websites and services. This repository helps users easily see changes over time through diffs, rather than relying on summaries or re-reading entire documents.

## Purpose
The main goal of Terms Tracker is to provide a transparent, chronological record of changes to Terms and Conditions. This enables users to:
- Quickly view the exact changes made to the documents.
- Compare the current terms with previous versions using Git diffs.
- Add new websites/services as a new file in order to start tracking.

## How It Works
1. **Tracking**: Terms and conditions of various services are periodically checked and updated.
2. **Committing Changes**: Updates are committed as changes occur, with clear commit messages summarizing the updates.
3. **Viewing Diffs**: Users can view diffs between commits to see precisely what was changed, added, or removed.

## Usage
To use this repository:
- **Clone** the repository to your local machine.
- **Navigate** to the service folder you are interested in.
- **Use** Git's diff functionality to see changes over time.

```bash
git diff <old-commit-id> <new-commit-id>
