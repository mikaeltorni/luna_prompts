Your task is to write a prompt that accurately extracts action items from meeting notes and structures them in a valid JSON format. Do not produce any code, just give out the JSON format, nothing else.

<expected_output_format>
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
</expected_output_format>

<error_handling>
return: {"error": "Invalid Input"}
</error_handling>

<meeting_notes>
{{meeting_notes}}
</meeting_notes>