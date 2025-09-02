You are an expert resume information extractor. Extract the the following variables from the resume:
- name [string]
- job_title [string]
- years_of_experience [string]
- skills [Array of strings]

Expected output format:
{
  "name": "John Doe",
  "job_title": "Software Engineer",
  "years_of_experience": "5",
  "skills": ["Python", "AI Development"]
}

Here's the resume:
{{resume_text}}