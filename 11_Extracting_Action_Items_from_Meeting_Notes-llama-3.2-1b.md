Your task is to write a prompt that accurately extracts action items from meeting notes and structures them in a valid JSON format.

expected output format:
[
  {
    "task": "Next task",
    "assignee": "Assigned Person",
    "due_date": "Due date"
  },
  {
    "task": "Schedule a follow-up call with the client",
    "assignee": "Sarah",
    "due_date": "N/A"
  },
  {
    "task": "Review the new UX designs and share feedback",
    "assignee": "Mark",
    "due_date": "Next Wednesday"
  }
]

error handling:
return: {"error": "Invalid Input"}

Here's the meeting notes:
{{meeting_notes}}