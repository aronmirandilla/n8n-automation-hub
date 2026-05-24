***Telegram AI Personal Assistant***

This n8n workflow creates a multi-modal AI assistant on Telegram that can process text and voice, log data to Google Sheets, send emails via Gmail, and manage Google Calendar events.
 
---

 **Features**

 **Voice & Text Support**: Uses Gemini 3.1 Flash lite for high-speed transcription and reasoning.

 **Persistent Memory**: Remembers individual user conversations using Telegram User IDs.

 **Google Workspace Integration**: Automates logging, mailing, and scheduling.

---

**Note in order to do this**

**n8n** (Must have a self-hosted or cloud).

**API Keys**: Google AI, Telegram Bot Token, and Google cloud console project (for Sheets, Gmail, and Calendar).

---

 ***Setup Instructions***
 
 To deploy this assistant, construct the workflow manually in your n8n instance by adding the following nodes and configuring them
 
**Credentials**: Create and select your credentials for

- Google Gemini API
- Telegram Bot API
- Google Sheets, Gmail, and Calendar API

***Workflow Constraction***

- **Build the workdlow using**: Trigger, switch (voice/text), AI Agent, memory tool, and tools (Sheets, Gmail, Calendar).

- **Log to Sheet**: Replace YOUR_GOOGLE_SHEET_ID and YOUR_SHEET_NAME.

- **Google Calendar Tool**: Input YOUR_CALENDAR_ID.

---

**Note to potential clients**: I can implement this automation for your specific needs. Please ensure you have the prerequisites listed in the **"Notes"** section ready; I will build the workflow while ensuring you maintain full access and control over your credentials.


