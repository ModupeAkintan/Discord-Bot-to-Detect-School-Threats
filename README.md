# Discord-Bot-to-Detect-School-Threats

Our group employs a two-stage classification system. The first stage uses Google’s Perspective API as the backbone of our threat moderation system. The messages are fed into the ’threat’ label of the API and assigned a rating between 0 and 1 based on how likely the message is to be a threat. 

Our group’s back-end technology use of Google’s Perspective API in combination with our Naive Bayes classifier is a powerful tandem of tools to help detect and classify threatening messages in the context of DMs and group chats as one might see on Facebook or WhatsApp. The implementation accomplishes our original goal of detecting threats and giving the moderator power of whether a threat should be escalated to the authorities or if other outcomes should be taken. It can successfully detect messages that appear in Unicode, foreign languages, or if a user edits a message. 
