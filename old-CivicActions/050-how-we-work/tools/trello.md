# Trello

## Overview

Trello is easy and intuitive. Install the extensions listed in that section below, and you'll figure out everything else you need to know as you go along.

If you like to live on the edge, skip this reading, but promise to come back in a week or two, maybe when you're a few days into a project that uses Trello, and read it.

- Introduction [video](https://www.youtube.com/watch?v=aaDf1RqeLfo&feature=youtu.be)

## About Trello

Trello is a collaborative task and project management tool that we use extensively at Bloom Works. Bloom Works has a free [team Trello account](https://trello.com/bloomworks) that we utilize for both internal and client projects.

Trello is very easy to use, and a robust feature set whose intuitive UI means the features don't get in the way of getting work done. It is well documented at <https://trello.com/guide>, but you probably won't need to read much documentation.

- Review the getting started [guide](https://trello.com/guide)
- "Use Trello like a Pro" [blog post](https://blog.trello.com/how-to-use-trello-like-a-pro)
- Keyboard shortcuts are listed [here](https://trello.com/shortcuts) Or just use the "?" shortcut to bring up that page any time

## The Basics (Naming Conventions and the general idea).

Trello has "boards" where work is tracked, using the metaphor of a whiteboard with columns taped with masking tape, and index card or sticky notes.

Work can be done by any member of the board, who need to be added by admins. Sometimes it's easier to have multiple admins from the Bloom Works team.

On each board there are "lists" which contain "cards". The only requirement for a card is a title, which is often written as a user story, or bug report, or other actionable task. This title shows up on the "front" of the card. When you click on the card it shows the "back" of the card (the metaphor is an index card on a whiteboard). The back of the card contain subtasks (often organized on checklist items), attachments, due dates, colored labels (categories), and comments (conversation in which you can @mention other members of the board). Cards can also contain references to GitHub pull requests, images (which can appear on the "front" of the card), and can be assigned to one or more people (either directly from the card, or by dragging and dropping their face from the right sidebar). All this data is summed up with icons on the front of the card.

Generally, cards move from left to right on a Trello board, through a series of lists, with the "Done" list at the far right. On many projects, you'll see lists like "Backlog", "Blocked", "Doing", "Code Review", "Ready for Client Review", "Approved", etc. The names of these lists tend to change project-to-project, and sometimes sprint-to-sprint, but the basic patterns are the same.

## Powerups and Extensions

Trello's business model is based on people paying for powerups, which are additional features. On most projects we rarely need more than one or two. Free accounts are limited to one powerup per board, so use it wisely. Luckily, browser extensions often provide the same functionality as powerups.

### Powerups

- GitHub Powerup: connect your board to a GitHub repo, and link out to Pull Requests. Small icons appear on the front of the card to show whether or not that card's icon has been merged.
- Voting Powerup: this is a great tool for taking straw polls on priorities. We often use the voting powerup on retrospectives to determine consensus on priorities.
- Calendar Powerup: if you assign due dates to cards, the calendar powerup adds a link to the header of your Trello board that displays all due dates in calendar format. It's mainly useful for very tight timelines, but not typically for Sprint-based work where most cards share the same deadline.

A full list of powerups is available at <https://trello.com/power-ups>

### Extensions

- [Show Card Numbers for Trello](https://chrome.google.com/webstore/detail/show-card-numbers-for-tre/pjhjdehkaggmpebggjonlhleidlodepi?hl=en)
- [Card Color Titles for Trello](https://chrome.google.com/webstore/detail/card-color-titles-for-tre/hpmobkglehhleflhaefmfajhbdnjmgim?hl=en) reminds you what the colored labels actually mean. This is particularly import if someone has gone all crazy with labels. Generally, it's good to keep the number of labels under 8. But the card color titles are still useful–especially because the label colors may mean something different on each board.
- [Boards for Trello](https://chrome.google.com/webstore/detail/t-boards/eknhddnoflchkcccjgdddmnimjggiona) adds a browser button to access any boards quickly. Personally, i prefer using my browser autocomplete feature (Ctrl-L to access your address bar, then T then Tab will turn your address autocomplete into a Trello search tool, with the most accessed Trello links first per your browser history.

## Slack add-ons.

The Trello integration for Slack is a great add-on for providing clickable summaries of Trello cards within Slack conversations. Use it! It needs to be added/configured for each Slack channel, by typing `/trello link [URL of Trello board]`. To use it, just copy/paste the URL of a card into a Slack channel. Type `/trello help` in Slack to get some other ideas, or check out [Trello's help page for Slack](http://help.trello.com/article/1049-slack-app)

## Best practices

- When you move a card to "Doing", assign yourself to it.
- Don't have 5 cards in "Doing" at once (this is more of a Scrum principle than Trello principle).
- Use [Markdown](http://help.trello.com/article/821-using-markdown-in-trello) in card descriptions (the first field on the back of the card).
- Make at least one other person on the board have the admin permissions.
- You can subscribe to a card (or even a whole board) without assigning yourself to that card. This will generate a lot of notifications, so use this wisely.
- Take screenshots of Trello Boards before and after Sprints (you'll probably have to zoom WAY out in your browser to see the whole thing).
- The Activity listing the right sidebar is great for getting the latest updates.
- Make the background of the board a color that is consistent with the other boards for the same project.

## Tips and tricks

- Learn the keyboard shortcuts! They are awesome, especially for adding labels, assigning cards, voting, archiving, navigating through cards, filtering cards, and saving text in any field. Shortcut "?" brings up list of keyboard shortcuts
- You can star your most used boards, which puts them at the top of trello.com
