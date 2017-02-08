# Interface Feedback

Effective interface feedback is essential to usability.

Feedback blocks are used to provide action-based feedback messages or to convey informational and/or critical account-related messages.

Feedback messages are categorized into four types based on severity:

- *Success:* indicates that an action processed successfully or that there are no account-related issues. The `success` helper class gives this block its green color.
- *Warning:* indicates that an action failed at this time that otherwise would be processed correctly. If the message is related to an account status then campaign sending ability might be affected to some extent. Use the `warning` class for the yellow background color.
- *Error:* indicates that an action failed completely. If the message is related to an account status then the campaigns will definitley not send. Use the `error` class for the red background color.
- *Info:* just provides information related to a performed action. Use the `info` class for the blue background color.
