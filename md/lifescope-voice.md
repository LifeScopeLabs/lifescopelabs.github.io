# [LIFESCOPE-VOICE](https://github.com/LifeScopeLabs/lifescope-voice)

## [Repository](https://github.com/LifeScopeLabs/lifescope-voice)

(development phase, low priority)

The LIFESCOPE API allows anyone to create a shared virtual space to access their memory and tell their stories.

This repo contains a series of voice command search applets written to extend the lifescope-app codebase as JS/Vue/Nuxt plugins.

Browser Web Speech API allows for speech recognition and synthesis support in Chrome, Edge, Firefox, Safari (partial). This API is super badass but no one ever uses it. 

# Requirements
- **MVP**: Respond to simple voice commands
	- Examples
		- "Run Saved Search: [Search Name]"
		- "Show me [View Name]"
		- "Add [Provider Name]"
		- "What was the last thing I did?"
		- "What did I do today?"
		- "Tell me about [Person Name] and I"
	- Voice Response
		- "28 Events match your saved search"
		- "Today's List of events. You received a message from Jane at 5:44 pm saying...."
- Deep Voice Search
	- **MVP**: Structured search terms (who, what, when, where, why)
	- Natural Language Processing.

- Passively capture voice data (speech text and recording) and store in LIFESCOPE.
- AI Storytelling.
	- "Here were the highlights from your trip to Hawaii...."

# Dependencies
- Vue/Nuxt compatible

# Examples

- [Web Speech API Documentation and Examples](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- [Speech Logger Web Speech API examples](https://speechlogger.appspot.com/developers/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjU3NTI3Mjg1LDEwMjYxMDY5MTYsLTE1Nz
gxNTIyNjAsMTg1MzMwNTQ5NiwyMDI3NjI5MzA0LC00NjI0Mzk2
NDYsLTE0NzU5MDU3NzIsMTY1NDE5MTk4NV19
-->