# Buttons and links

Links and buttons provide important ways to navigate users across a website. Links provide a simple link to content that exists on another page, and simply indicate that there is a next page to go to. -Buttons- indicate a specific action you want a user to take, such as filling out a form or reading a case study.

## Guidelines

- Links should be written in sentence case. For example, "Watch the Video" is incorrect, while "Watch the video" is correct.
- Links should be descriptive and not conversational. For example do not use [yes] and [no], instead [cancel] [delete]
- To ensure accessibility to all audiences, including those using screen readers or other assistive devices, links should always be descriptive of the action and/or page that they link to. Never use a link that says simply “click here” or “here.” Be cautious with links like “learn more,” “visit,” or other vague terms.
- When creating buttons, aim for concise and descriptive. Avoid full sentences, i.e. “read the full case study on LinkedIn.”
- Use buttons primarily for specific calls to action.
- Prioritize button usage so that users understand the primary action you want to take. Avoid having several primary buttons in a row.

## Buttons

Buttons are used to signify calls to action and show a clear next step for users. They should be used to designate a link as a primary or secondary call to action on the page. For buttons, labels should be short (20 characters or less), and will display in all caps.

Pega websites use three primary button styles: Raised, Flat and Subtle. Helper classes are available to accommodate different background colors

*Raised buttons* add dimension to mostly flat layouts. They emphasize functions on busy or wide spaces. Ideally, a raised button should only be used 1-2 times in a layout to focus the user on the main CTA.

```
<a class="c-button c-button--raised u-margin-bottom">
  Button
</a>
```

*Flat buttons* act as a secondary button to the raised button. They should be used to designate secondary calls to action.

```
<a class="c-button c-button--flat u-margin-bottom">
  Button
</a>
```

*Subtle buttons* appear as links in all caps with no outline. They should be used whenever tertiary actions are present on the page, and to reduce the priority of a call to action in a main area.

```
<a class="c-button c-button--subtle u-margin-bottom">
  Button
</a>
```

## Links

Links are primarily used to send users to another page or hyperlink outside of the website. Links should be used for tertiary calls to action, and for when the description of a link requires more than 20 characters. Links should be written in sentence case. For example, "Watch the Video" is incorrect, while "Watch the video" is correct.
