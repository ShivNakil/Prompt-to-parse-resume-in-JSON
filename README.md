# Promt to parse resume into json

I will provide you with a resume. Please parse the content and convert it into the following JSON format:

```json
{
  "personal_info": {
    "name": "Full Name",
    "location": "City, State, Country",
    "contact": {
      "phone": "Phone Number",
      "email": "Email Address"
    },
    "date_of_birth": "Date of Birth",
    "social_profiles": {
      "linkedin": "LinkedIn URL",
      "github": "GitHub URL",
      "codechef": "CodeChef URL",
      "personal_website": "Personal Website URL"
    }
  },
  "education": [
    {
      "degree": "Degree Name",
      "field": "Field of Study",
      "institution": "Institution Name",
      "cgpa_or_percentage": "CGPA or Percentage",
      "year_of_completion": "Year of Completion",
      "location": "City, State, Country"
    }
  ],
  "skills": [
    "Skill1",
    "Skill2",
    "Skill3"
  ],
  "languages": [
    "Language1",
    "Language2",
    "Language3"
  ],
  "frameworks_technologies": [
    "Framework1",
    "Technology1"
  ],
  "internships": [
    {
      "company": "Company Name",
      "location": "City, State, Country",
      "position": "Internship Position",
      "start_date": "Start Date",
      "end_date": "End Date",
      "description": "Brief description of the work done during the internship."
    }
  ],
  "projects": [
    {
      "title": "Project Title",
      "duration": "Duration",
      "description": "Brief description of the project."
    }
  ],
  "courses_achievements": [
    {
      "course_or_achievement": "Course or Achievement Title",
      "institution_or_event": "Institution or Event Name",
      "description": "Brief description of the course or achievement."
    }
  ]
}
```